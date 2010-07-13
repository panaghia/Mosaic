Mosaic
===========

Mosaic Plugin creates a snake-like effect morphing sub-patterns of an image.


How to use
----------

The use of this plugin is quite easy.
You should create a DIV and include the Mosaic stylesheet (with .MBox class) and declare an instance of Mosaic class.

Example usage:

	mosaic = new Mosaic(
	{
	            base: $('myDiv'),
	            image: "megan.png",
	            width: 483,
	            height: 356,
	            startColor: '#930',
	            endColor: '#000',
	            startAlpha:.7,
	            endAlpha: .1,
	            hacked: true
	            
	});
	
	mosaic.setDuration(400);
	mosaic.setTransition(Fx.Transitions.Sine.easeOut);
	mosaic.render();


Screenshots
-----------


![Screenshot 1](http://panaghia.it/imgs/mosaic_example.jpg)



