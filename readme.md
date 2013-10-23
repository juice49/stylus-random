# Stylus Random

This is a plugin that exposes Math.random() to your Stylus files. Pass a `min` and `max` value to get a random number in a range.

Example:

    use('path/to/stylus-random')

    .node
    	height random(100, 500) px

In my opinion this functionality should be available in Stylus by default.