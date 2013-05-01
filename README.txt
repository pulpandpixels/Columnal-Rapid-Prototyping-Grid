====================
COLUMNAL GRID SYSTEM
====================

Columnal is a project created by Pulp+Pixels - www.pulpandpixels.com

The Columnal CSS grid system is a "remix" of a couple others with some custom code thrown in. The elastic grid system is borrowed from what was cssgrid.net, while some code inspiration (and the idea for subcolumns) are taken from 960.gs. The CSS reset is the famous reset created by the CSS rockstar, Eric Meyer.

Please visit columnal.com for more information on the grid system.

===============================================

The Columnal CSS includes necessary at the top of an html page should appear like the demo page, but similar to this: 

<meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  
<!-- The Columnal Grid (base, load first) -->
	<link rel="stylesheet" href="css/columnal.css" type="text/css" media="screen" />

<!-- Page building tools - Gray box colors and page debugging tools -->
    <link rel="stylesheet" href="css/build.css" type="text/css" media="screen" />

====================
CSS FILES
====================

columnal.css
	• HTML Reset (Eric Meyer HTML Reset)
	• Type and image settings (Columnal comes with basic type presets, but custom type control is encouraged, another option is a CSS type framework such as Tripoli CSS from devkick
    • Common base code for the CSS framework - this is where the columns are defined across browsers, and basic functions are added. Also includes Eric Meyer reset.
	• Mobile stylesheet (moves the layout to a single column for mobile viewing)

custom.css
    • Place custom page layouts here - see notes in file

build.css
	• Page building tools - Gray box colors and page debugging tools