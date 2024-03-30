# j-sliding-banner
jQuery banner plugin for websites. Easy to use, responsive design, and fully customizable.

### Screenshots
![alt tag](https://github.com/waiyanhein/j-sliding-banner/blob/master/banner.png)

### Dependency
Only Jquery is required. 

### How to use

#### Step. 1 - import dependencies
Download jslidingbanner.zip and include j-sliding-banner.min.css, the jQuery JavaScript file, and j-sliding-banner.min.js in the HTML header. Optionally, you can also add bootstrap.css.

#### Step. 2 - Create  html in the following format
```html
<div id="banner">
		<div class="sliding-banner-container">
			<ul class="sliding-banner">
				<li class="sliding-banner-item">
					<img class='sliding-banner-img' src="image/img_1.png">
					<div class="sliding-banner-content">
						<div>
							//Whatever content you want goes here
						</div>
					</div>
				</li>
				<li class="sliding-banner-item">
					<img class="sliding-banner-img" src="image/img_2.png">
					<div class="sliding-banner-content">
						<div>
							//Whatever content you want goes here
						</div>
					</div>
				</li>
				<li class="sliding-banner-item">
					<img class="sliding-banner-img" src="image/img_3.png">
					<div class="sliding-banner-content">
						<div>
							 //Whatever content you want goes here
						</div>
					</div>
				</li>
			</ul>
		</div>
	</div>
```
#### Step.3 initialize
``
$('#banner').jSlidingBanner();
``

#### That's it



## Options
### Example of using option
``
$('#banner').jSlidingBanner({ slideAnimationSpeed : 500 });
``

#### setOverlay - TRUE/FALSE
If set to false, the dark overlay on the image will be removed. If set to true, the dark overlay will be added. The default value is true.

#### overlayColor - string(color code or color name)
This is the color value for the overlay. The default is "#000000". You can set the overlay to any color you desire, such as red, green, or any other color.

#### displayImageDuration - integer(Milliseconds)
This option sets the duration, in milliseconds, for how long an image of the slider will be displayed. The default is 4000 milliseconds, equivalent to 4 seconds.

#### slideAnimationSpeed - integer(Milliseconds)
This option sets the speed at which the slider will animate when transitioning from one image to another. The default is 500 milliseconds, which is equivalent to half a second.


