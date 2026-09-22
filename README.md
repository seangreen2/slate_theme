## Slate Theme for Home Assistant
Full Home Assistant configuration files can be found [here](https://github.com/seangreen2/home_assistant).

---

### Installation

Download the `slate.yaml` file from inside the `themes` directory here to your local `themes` directory.

Make sure to add `themes: !include_dir_merge_named themes` under `frontend:` in your `config.yaml` like so:

```
frontend:
  themes: !include_dir_merge_named themes
```
  
Restart Home Assistant and select your theme by clicking on your user's profile circle in the bottom left.

### Making map cards readable

Slate declares a dark mode, so Home Assistant map cards use their dark map style by default. If a map card is too dark to read, set its `theme_mode` to `light`:

```yaml
type: map
theme_mode: light
entities:
  - person.example
```

This keeps the Slate theme for the dashboard while using the light map style for that card.

Recommended colors for graphs, bars, etc.
  - Blue: #2980b9
  - Yellow: #b58e31
  - Red: #b83829
  - Green: #70a03c

---

![1](https://i.imgur.com/mN2CWjr.jpeg)
![2](https://i.imgur.com/8PTwdXW.jpeg)
![3](https://i.imgur.com/YmjjfMt.jpeg)
![4](https://i.imgur.com/ZdSqZI0.png)
