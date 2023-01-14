---
description: How to install webretro
---

# Installing Webretro

Webretro is not included by default.

To install webretro, use the install script:

```bash
./webretro.sh
```


If it says `./webretro.sh: Permission denied` run:
```bash
chmod u+x webretro.sh
```

You can add webretro ROMS to the games page just like normal games, but with this format instead


```json
{
    "img": "./img/gs/game.jpg",
    "location": "./source/webretro/?core=autodetect&rom=romfile",
    "category": "Category",
    "title": "Game Title"
},
```