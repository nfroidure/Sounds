Sounds
==============

Sounds is a simple JavaScript library playing sounds. Modern browsers only, experimental.

```js
var soundManager=new Sounds('media/sounds',function() {
	console.log('All sounds loaded !');
	// play tadaa 3 times
	soundManager.play('tadaaa',3);
	// let's play good background sound
	soundManager.play('highwaytohell',Infinity);
	});
soundManager.register('highwaytohell');
soundManager.register('supersound1');
soundManager.register('supersound2');
soundManager.register('tadaaa');
```

Licence
--------------
GNU/GPL
