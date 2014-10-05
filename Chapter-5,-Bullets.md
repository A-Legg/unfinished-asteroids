I am really glad we have hired you. Everything goes as expected.

To the point.

Press SPACE to fire. Well  - Mike was in a hurry and we have this white rectangles instead of bullets.
Could you please replace them with a proper graphics? Maybe this will help you:

> `Entities/Bullet.js` is the file. The spritesheet with bullet graphics can be found in `images/spritesheet.png`. I've heard that this game will have to support two players at later stage - you can get a bullet team accessing `this.team` (0 blue, 1 red). I already have similar thing in `Entities/Ship.js` - except bullets are just balls so you don't have to rotate them.

> Anyway I am using [slightly enchanted](http://canvasquery.com/basics) canvas (`app.layer`) so you can either use [drawImage](http://tutorials.jenkov.com/html5-canvas/images.html#drawing-parts-of-images) or [drawRegion](http://canvasquery.com/drawRegion).