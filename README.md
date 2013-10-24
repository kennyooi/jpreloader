jpreloader
==========

jPreLoader plugin is a jQuery preloader to preload images for website. It create a preloading screen (aka. splash screen) for your website before all your images, and background images are fully loaded. It will come in handy when you wish to preload all the images on your page before exposed to user, especially for those games websites.

Demo Page
=========

http://www.inwebson.com/demo/jpreloader-v2/

Features
========

- Full page Loading Screen.
- Progress bar with progress percentage.
- Display custom Splash Screen during loading process.
- Preload all images in <img> tag as well as in Stylesheet.
- Using CSS to customize.
- Debug mode to check for broken images.

Configuration
=============

	.jPreLoader( [Options] [, callback] )
	
Options
-------

- **showSplash** - Enables showing the Splash Screen. *(Default: true)*
- **showPercentage** - Enables showing the progress percentage. *(Default: true)*
- **loaderVPos** - Vertical position from top of progress bar. *(Default: 75%)*
- **splashVPos** - Vertical position from top of Splash Screen. *(Default: 35%)*
- **splashID** - Selected element of Splash Screen Content. *(Default: #jpreContent)*
- **splashFunction** - This function is called once the Splash Screen is created. You can use this to animate the Splash Screen. *(Default: null)*
- **autoClose** - Should jPreLoader close by itself once preload completed? If no user have to click on button to close the jPreLoader. *(Default: true)*
- **closeBtnText** - Text to be show inside close button if autoClose is false. *(Default: Start!)*
- **onetimeLoad** - Should jPreLoader preload images for new user only? (using cookie to check and will expired once user close their browser) *(Default: false)*
- **debugMode** - Enable this only if you want to check for broken images. *(Default: false)*

For more info on how to set up and configuration, do visit http://www.inwebson.com/jquery/jpreloader-a-preloading-screen-to-preload-images/
