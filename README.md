Lizbert
=======
A game all about Lizbert! ![The Lizbert](https://github.com/adamretter/lizbert/raw/master/images/liz-sprite-stand.png "The LizBert")

The game is made using the [Quintus HTML5 game engine](http://html5quintus.com/). Tiles were taken from [Platformer Art Deluxe](http://opengameart.org/content/platformer-art-deluxe). Unfortunately, the game can only be played from a Web Server due to the XSS restrictions of JavaScript. There are no server-side components however and you only need a simple Web Server to serve the static content ([NGINX](http://wiki.nginx.org/Main) works just fine). The game has been tested in Chrome v30.0.1599.101 and Firefox v24. Spritesheets were produced with [Spriter](https://github.com/cykod/Spriter), tile layers using [Tiled](http://www.mapeditor.org/), and the images using [Gimp](http://www.gimp.org).


Quintus TileLayer Details
-------------------------
tileW: 35
tileH: 35

Tile Details (textures1.png)
----------------------------
width: 72
height: 72
spacing: 0
margin: 0

TODO
----
* Make head move around and say "Bored now!" when lizbert is stationary for two long.
* Make head bob slightly as lizbert walks
* Add things for lizbert to collect
* Add lizbery enemies