# h5 project
just a few note while learning h5

## h5 video and audio leanring note
h5 video and audio campatibility let you creating multimedia on webpage more easily than ever before.
even currently there are just a few codec are supported:
	* ogg
	* mp4 & mp3
	* and more

````
video & audio
````

## [`requestAnimationFrame`] new api
````
if (!window.requestAnimationFrame)
	window.requestAnimationFrame = function (callback, element) {
	    var currTime = new Date().getTime();
	    var timeToCall = Math.max(0, 16 - (currTime - lastTime));
	    var id = window.setTimeout(function () { callback(currTime + timeToCall); }, timeToCall);
	    lastTime = currTime + timeToCall;
	    return id;
	};
````

## h5 canvas learning note
[`canvas`] is first introduced by apple.

## svg is an format only
`svg` vs canvas
