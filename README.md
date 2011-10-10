# Fluid Baseline Grid [http://fluidbaselinegrid.com](http://fluidbaselinegrid.com)
###The Fluid Baseline Grid System is an HTML5 & CSS3 development kit that provides a solid foundation to quickly design websites with ease.

The FBG system was built with typographic standards in mind and combines principals of fluid-column layouts, baseline grids and mobile-first responsive design into a resolution independent and device agnostic framework. It is packed with CSS normalization, beautiful typographic standards, corrected bugs, common browser inconsistencies and improved usability. You can finally have your cake and eat it too, all while making awesome websites.

## Fluid Columns
The FBG system facilitates creativity by providing a framework for composition. Grid systems create visual rhythm and structural balance to enhance the experience with predictable patterns.
FBG is defaulted to a minimal 3-column folding grid, which is easy to work with and divided into equal portions, 31.333% wide with 2% wide gutters between columns. This is a starting point, not a standard, so we encourage you to change the columns as your project requires.

## Baseline Grid
The typography of FBG is designed to establish a typographic hierarchy that improves readability and creates harmony within the text. Measure, leading, vertical rhythm, emphasis and scale are something we obsess about.

The primary font is Georgia, but the font stack can be easily changed. Paragraphs are set at a 16px base with 150% (24px) line height to improve readability and improve the appearance of text. We encourage you to change the base font size and line height to suit your needs.

## Responsive Design
The FBG is designed for mobile first. CSS styles are scaled up from the minimum instead of scaled down from the maximum through the use of media queries. IE6/7/8 do not support media queries, so Respond.js is used to polyfill.

###Common Break Points
* 320 px | Mobile portrait
* 480 px | Mobile landscape
* 600 px | Small tablet
* 768 px | Tablet portrait
* 1024 px | Tablet landscape/Netbook
* 1280 px & greater | Desktop

## Normalize CSS
Reset vs. Normalize? Most web designers use either the Eric Meyer Reset or the YUI Reset, but a reset doesn't fix cross-browser inconsistencies or preserve useful defaults. Normalizing CSS allows for the preservation of useful defaults, while correcting bugs, fixing common browser inconsistencies and improving usability. Many thanks to Nicolas Gallagher and Jonathan Neal for researching the differences between default browser styles in order to precisely target only the styles that need normalizing.

## File Structure
The file structure for FBG is straight-forward and contains only the minimum files to get started.

* css [folder]
	* style.css: Base styles of FBG for layout, grid, type and media queries
* JavaScript [Google CDN]
	* jQuery 1.6.2: High-speed load of the latest minimized verson of jQuery from Google CDN
*HTML5 shiv: HTML5 IE enabling script and print protector from Google CDN
* js [folder]
	* Respond.js v1.0.1: Lightweight polyfill for CSS3 Media Queries (for IE 6/7/8)
* images [folder]:
	* grid_bg.gif: Repeating background for vertical rhythm testing purposes
* index.html: Base HTML page that includes only necessary minimal markup
* favicon.ico: Standard 16x16 favicon
* apple-touch-icon (x3): Maximum touch-icon support. Sizes for iPhone 3, iPad and iPhone 4 retina
* robots.txt: SEO, search-crawler file

## Usage

The code for FBG is simple, lightweight, and non-obtrusive, which allows it to be easily modified for each project. The default is based on a 3-column folding layout. 1 column for mobile devices, 2 columns for tablets and 3 columns for desktops and beyond. The only necessary provision is to add either <code>class="g1"</code>, <code>class="g2"</code> or <code>class="g3"</code> to each <code>&lt;div&gt;</code> you would like to make a column.

<pre>&lt;div&gt;
	&lt;div class="g2"&gt;
		...
	&lt;/div&gt;
	&lt;div class="g3"&gt;
		...
	&lt;/div&gt;

	&lt;div class="g1"&gt;
		...
	&lt;/div&gt;
&lt;/div&gt;</pre>

## Feedback
Feedback, questions or thoughts about FBG? Email us and we will get back to you as soon as possible.

## Browser & Device Support
The FBG System is cross-browser compatible and device independent: Firefox 3.5+, Opera 11+, Chrome 11+, Safari 5+ and Internet Explorer 6+.

## Changelog
* v1.0.0 (9/22/2011): Initial release of FBG.
* v1.0.1 (10/09/2011): Shifted grid_bg to align with text baseline.
* v1.0.1 (10/09/2011): Adjusted text size for screen size over 1400px.

## Attribution
Many thanks to Richard Rutter, Ethan Marcotte, Paul Irish, Remy Sharp, Faruk Ates, Dan Cederholm, Nicolas Gallagher and Eric Meyer.

## License:
### Components:

* jQuery: MIT/GPL licenses
* Respond.js MIT/GPL licenses
* HTML5shiv MIT/GPL licenses

### License:
* The code and design are released into public domain and are free to use under Unlicense. [Unlicense](http://unlicense.org)