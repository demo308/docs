# Custom themes and games

How to custom themes and games

## Add Games

More games can be added to Incognito by editing gs.json in a format, displayed in this example:

```json
{
  "img": "./img/gs/game.jpg",
  "location": "./source/gameloc/",
  "category": "Category",
  "title": "Game Title"
},
````

`img` images are only located in `/img/gs/`.

Category should be set for the game you are adding

It can be set to:

* multi
* web
* indie
* n64
* gfn

You can also add

`"featured": true`

to make a entry featured.

Working example:

```json
{
  "img": "./img/gs/flappybird.jpg",
  "location": "/source/flappybird/",
  "category": "web",
  "title": "Flappy Bird"
},
```

## Add Themes

To add a theme, first open the file in `static/css/appearance.css`