CloudyJS
========

Jelly Bean Easter Egg-like. Work in progress.

How to use
----------

You need to provide an image to CloudyJS. It will be displayed on screen.
Then, you just have to call the `start()` method.

Here's an example to start CloudyJS with [Konami-JS](https://github.com/snaptortoise/konami-js) :

```
var clouds = new Cloudy('path/to/image.png');
var easterEgg = new Konami(function() { 
    clouds.start();
});
```
