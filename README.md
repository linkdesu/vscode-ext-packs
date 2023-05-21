# Link's VSCode Extension Packs Collection

![](./logos/Gold_Chest_(old).png)
![](./logos/Hallowed_Chest_(old).png)
![](./logos/Ivy_Chest_(old).png)
![](./logos/Jungle_Chest_(old).png)
![](./logos/Meteorite_Chest_(old).png)
![](./logos/Mushroom_Chest_(old).webp)
![](./logos/Obsidian_Chest_(old).png)
![](./logos/Pumpkin_Chest_(old).png)
![](./logos/Shadewood_Chest_(old).png)
![](./logos/Shadow_Chest_(old).png)
![](./logos/Steampunk_Chest_(old).png)
![](./logos/Water_Chest_(old).webp)


Here are my VSCode extension packs 🧰. Each of them are focus on some domain in development except the core-pack.
The reason why I made my own extension packs is mainly for keep VSCode in blazing fast status.

Enjoy youself with these packs, and feel free to fork and made your every own packs. 👍


## Usage

### Generating extension files

```bash
npm run build
```

This will create VSCode extension bundles in `dist/`. All bundle files ends with `.vsix`.

### Install extension from files

```bash
code --install-extension dist/core-pack.vsix
code --install-extension dist/note-pack.vsix
code --install-extension dist/util-pack.vsix
code --install-extension dist/bash-pack.vsix
code --install-extension dist/rust-pack.vsix
code --install-extension dist/python-pack.vsix
code --install-extension dist/vue-pack.vsix
```

> ⚠️ These commands should be executed one by one without using `npm run`.


## Logos

All logos are not design by myself but come from one of my favoriate game named [Terraria](https://terraria.org/). And the images are downloaded from [terraria.wiki.gg](https://terraria.wiki.gg/wiki/Category:Item_images).


## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2022-present Link Xie
