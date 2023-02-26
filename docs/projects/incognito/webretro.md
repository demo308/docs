---
description: How to install webretro
---

# Installing Webretro

Webretro is not included by default.

To install webretro, use the install script:

* Linux - `npm run install-webretro-linux`
* Windows - `npm run install-webretro-win`

:::note

If you get a error that says `./src/webretro.sh: Permission denied`, run

```bash
chmod u+x ./src/webretro.sh
```

:::

You can add webretro ROMS to the games page just like normal games, but with this format instead


```json
{
    "img": "./img/gs/game.jpg",
    "location": "./source/webretro/?core=autodetect&rom=romfile",
    "category": "Category",
    "title": "Game Title"
},
```