Lizbert
=======
A game all about Lizbert! ![The Lizbert](https://github.com/adamretter/lizbert/raw/master/images/liz-sprite-stand.png "The LizBert")

The game is made using the [Quintus HTML5 game engine](http://html5quintus.com/). Tiles were taken from [Platformer Art Deluxe](http://opengameart.org/content/platformer-art-deluxe). Unfortunately, the game can only be played from a Web Server due to the XSS restrictions of JavaScript. There are no server-side components however and you only need a simple Web Server to serve the static content ([NGINX](http://wiki.nginx.org/Main) works just fine). The game has been tested in Chrome v30.0.1599.101 and Firefox v24. Spritesheets were produced with [Spriter](https://github.com/cykod/Spriter), tile layers using [Tiled](http://www.mapeditor.org/), and the images using [Gimp](http://www.gimp.org).


Quintus TileLayer Details
-------------------------
tileW: 72
tileH: 72
cx: 2
cy: 2

Note - tileW and tileH should probably be 70!


Tiled TileSet Details (textures1.png)
-------------------------------------
width: 70
height: 70
spacing: 2
margin: 2


TODO
----
* Slow down the speaking animation for 'Bored Now' sprites
* Add things for Lizbert to collect (Academic Papers / Teapots)
* Add Lizbert Energy bar... a.k.a. Liz Snacks! Liz gets hungry as she moves about! Liz snacks include - Crisps, Peanuts, Bananas and 
* Add Lizbert enemies (Bees or Wasps / Alarm Clocks / Polystrene? / Rustly Polyester Trousers and Jackets?)
* Need "Ouch!" / "Bad!" sound and anim when hit enemy or water
* Give Lizbert n lives
* Need background story and plot for start of game
* Add background picture
* Add scoring
* Add Leaderboard (may need server-side component to store and remember scores)