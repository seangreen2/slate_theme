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

Recommended colors for graphs, bars, etc.
  - Blue: #2980b9
  - Yellow: #b58e31
  - Red: #b83829
  - Green: #70a03c

---

![1](https://i.imgur.com/DpQZ6eq.png)
![2](https://i.imgur.com/n3ApBNK.png)
![3](https://i.imgur.com/pnEflUd.jpg)
