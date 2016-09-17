# j-sliding-banner
Jquery banner plugin for websites. Easy to use and fully customizable.

###Screenshots
![alt tag](https://github.com/waiyanhein/j-sliding-banner/blob/master/banner.png)

###Dependency
Only Jquery is required. 

###How to use

####Step. 1 - import dependencies
Include j-sliding-banner.min.css,Jquery js file and j-sliding-banner.min.js in the header of HTML. You can add bootstrap.css if you want to.

####Step. 2 - Create  html in the following format
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
####Step.3 initialize like below in Javascript
``
$(function(){
	$('#banner').jSlidingBanner();
})
``

####That's it. You are done. You can reference on the example project as well. It is pretty simple.



##Options
###Example of using option
``
$(function(){
	$('#banner').jSlidingBanner({ slideAnimationSpeed : 500 });
})
``

####setOverlay - TRUE/FALSE
If you set it to false, dark overlay on image will be removed. If true, dark overlay will be added. Default is true.

####overlayColor - string(color code or color name)
This is the color value for overlay. Default is "#000000". You can set overlay to whatever color you want. Red or green or whatever.

####displayImageDuration - integer(Milliseconds)
This option sets how long an image of slider will be displayed in milliseconds. Default is 4000 milliseconds. So 4 seconds.

####slideAnimationSpeed - integer(Milliseconds)
This option sets how fast slider will animate when it changes from one image to another. Default is 500 milliseconds. So half a second.


