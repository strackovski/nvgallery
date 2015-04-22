# nvgallery
A jQuery plugin for creating galleries fast. Visit the [nvgallery](http://www.envee.eu/nvgallery/) page for a detailed documentation and to see nvgallery in action.

### Dependencies
 - jQuery
 - [FontAwesome](http://www.fontawesome.io/) (included in libs folder)


### How to use the plugin
##### 1. Make an array of images for the gallery
<pre>var myPictures = [
	{path: ‘images/image1.png’, description:’Just a picture’},
	{path: ‘images/image2.png’, Another photo I took;}
];</pre>

##### 2. Make a div element where the gallery will show up
<pre>&#60div class=“wrap”&#62&#60/div&#62</pre>
Note: You can set its width, otherwise it will take 100% of width of the parent.

##### 3. Call plugin
Call the plugin on the created div, inside your document.ready() and pass the images array as an argument.
<pre>$(‘.wrap’).nvgallery(myPictures)</pre>

### License

Released under the MIT license. Please see the LICENSE file provided with this project.