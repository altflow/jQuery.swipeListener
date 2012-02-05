jQuery.swipeListener.js
----

jQuery plugin to assign swipe event listener.

### Usage
	$(element).swipeListener(option);

Example:

    $("#target").swipeListener({
		swipeLeft: function() { alert("you just swiped left."); }
	});

### Options

- __duration__ : the time from touchstart to touchend must be in this period.
- __minX__ : the position moved more than this value to deem swipe right or left
- __minY__ : the position must be moved more than this value to deem swipe up or down
- __swipeUp__ : callback function that is invoked when swipe up event happens
- __swipeDown__ : callback function for swipe down
- __swipeLeft__ : callback function for swipe left
- __swipeRight__ : callback function for swipe right
