# jQuery AnySlider 1.5.2-beta
AnySlider is a jQuery plugin which allows you to create a slider for any kind of HTML content.

http://jonathanwilsson.com/anyslider/

## Features
* Continuous autoplay.
* Custom easings.
* Fade or slide transition.
* Highly customizable appearance and lots of options.
* Keyboard navigation.
* Multiple sliders on one page supported.
* Navigation bullets.
* No CSS or HTML-structure enforced, you're 100% in charge.
* Slide any content or using any element. HTML, images and YouTube clips. Or mix &lt;div&gt;s, &lt;span&gt;s and &lt;section&gt;s. AnySlider doesn't care.
* Small, 1.4 kB minified and gzipped.
* Supported in all major browsers.
* Touch support.

## Options
* afterChange (Default function ()) function A function to call after each slide change.
* afterSetup (Default function ()) function A function to call after the slider has been setup.
* animation (Default slide") string Transition, one of the following:
	* fade Fades between slides.
	* slide A sliding aniamtion between slides.
* beforeChange (Default function ()) function A function to call before each slide change.
* bullets (Default true) boolean Whether or not to display navigation bullets. Setting this to false will prevent the bullets from being drawn at all.
* easing (Default "swing") string Name of a custom easing. For example via the jQuery Easing plugin. Only used when "animation" is "slide" or "fadeSlide".
* interval (Default 5000) integer Number of milliseconds to pause on each slide. Setting this option to 0 will disable autoplay.
* keyboardNav (Default true) boolean Allow for keyboard navigation using the left and right arrow keys.
* nextLabel (Default "Next slide") string Label for the next button.
* pauseOnHover (Default true) boolean Pause the autoplay on hover?
* prevLabel (Default "Previous slide") string Label for the previous button.
* responsive (Default true) boolean Whether to enable responsive support.
* rtl (Default false) boolean Whether to slide right-to-left instead of left-to-right when autoplay is enabled.
* showControls (Default true) boolean Show/hide controls. Setting this to false will prevent the controls from being drawn at all.
* speed (Default 400) int The animation time in milliseconds. Setting this option to 0 will disable animation.
* startSlide (Default 1) int Number of the starting slide. Starting from 1.
* touch (Default true) boolean Whether to enable the ability to swipe between slides.

Minimum required jQuery version is 1.5.0.

## License
Free to use and abuse under the [MIT license](http://www.opensource.org/licenses/mit-license.php).

## Changelog
### 1.5.2
*

### 1.5.1
* Fixed a compatibility issue with jQuery 1.9.

### 1.5.0
* AnySlider is now responsive!
* The option "showOnHover" has been removed. Arrows are only drawn if "showControls" is true. The ability to show/hide controls is now handled by CSS.
* The navigation bullets have been moved outside the slider element to allow for better control of the positioning.
* Other bugfixes, optimizations and improvements.

### 1.4.3
* Fixed an issue where the slider would crash in older versions of jQuery.
* Fixed an issue where the navigation bullets weren't correctly updated.
* Added the following callbacks:
	* beforeChange which triggers before a slide changes.
	* afterChange which triggers after a slide changes.
	* afterSetup which triggers after the slider has setup completely.

### 1.4.2
* Added fade transition.

### 1.4.1
* Changed the arrows from &lt;span&gt;s to &lt;a&gt;s for improved accessibility.
* Added the ability to choose the starting slide.
* Some code enhancements.

### 1.4
* Added the ability to swipe between slides.
* Increased the minimum required jQuery version to 1.5.
* Changed the following class names:
    * prev-arrow to as-prev-arrow
    * next-arrow to as-next-arrow
    * active to as-active

### 1.3.2
* Fixed an issue where AnySlider would autoplay when there was only one slide.
* Added navigation bullets.
* Added the "rtl" option to control slide direction when autoplay is enabled.

### 1.3.1
* Added support for custom easings via the jQuery Easing plugin.
* Added autoplay support. Check out the "interval" and "pauseOnHover" options.
* Restructured the CSS to help with the setup of AnySlider.

### 1.3
* Rewrote most of the script.
* The slider is now "infinite" and will always scroll in the same direction.

### 1.2.2
* Fixed an issue where the "speed" option wasn't honored.

### 1.2.1
* AnySlider now support several sliders on one page.
* Removed the IDs from the arrow elements. Instead, they now have classes of "prev-arrow" and "next-arrow" respectivly.
* The ID "slide-inner" is now a class instead.
* Fixed an issue where animations could be "queued" and would be run several times.

### 1.2
* Finally added a "speed" option.
* Various code improvements.

### 1.1.2
* Enhanced the options to always show/hide arrows or just on hover.
* Minor code cleanup.

### 1.1
* New arrows.
* Added some options:
    * Always show/hide arrows
    * Enable/disable keyboard navigation
    * Custom labels for the controls
* Fixed a minor bug were keyboard codes had to be converted into a string.
* Separated options from internal variables.

### 1.0.1
* Rewrote bits of the code to perform better.

### 1.0
* Initial release.

## Copyright
Copyright 2011-2013 Jonathan Wilsson.