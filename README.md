# timer.js
A simple timer framework

# Status 
 * started
 * running
 * stopped
 * completed

# Functions
 * `setAction()`：some tasks you want to do
 * `start()`：start the timer
 * `stop()`：stop the timer
 * `complete()`：once the tasks done, it will be triggered
 * `status()`：retrieve the current status

# Code example
```javascript
var timer = new Timer();
timer.setAction(function() {
	// @TODO
	
	// To start the timer in next second, 
	// without this line the task will be executed for once
	this.start();
});
timer.start().complete(function(){
	// @TODO
});
	
```
```javascript
var timer = new Timer(1,function(){
	// @TODO
		  
	// To start the timer in next second, 
	// without this line the task will be executed for once
	this.start();
});
timer.start().complete(function(){
	// @TODO
});


```
