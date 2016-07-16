# Making beautiful scientific graphics using Inkscape

Inkscape is a cross-platform graphical editor for SVG files.

## A few notes about SVGs
* SVG is a file format you can open in modern browsers.
* It is a vector format, which means you don't lose resolution when you zoom in. This is in contrast to bitmap (a.k.a. pixel) formats such as PNG or JPG.
* It is text-based format.
* Your plotting program may make SVG. If it doesn't, then perhaps it makes EPS or PDF files, which can be imported by Inkscape.

<!--
## Overall layout of an Inkscape session
* Tools are on the left
* Top panel depends on what you are doing, it's called the Tool Control Bar
I suggest using a two-button mouse with a scroll wheel.
-->

## Moving around in your document
* The magnifying glass enables zooming with a click or a rectangle selection. Shift-click zooms out.
* View menu has lots of options for zooming. 5 zooms to frame your document.
* Zoom in and out using Control and scroll wheel.

## Selecting objects
* Click to select an object.
* Shift-click (i.e. click while holding down Shift) to add an object to the selection.
* Click and drag to select objects in a box.
* Tab selects the next object. Shift-tab selects the previous object.

## Modifying objects
* Move your selection by dragging. Control-drag only moves in one direction.
* Or move your selection using the arrow keys. Alt-arrow moves items a small amount.
* Stretch using arrows around object. Hold the Control key to keep aspect ratio.
* Click objects again to be able to rotate and skew them.
* Objects have an order of what is on top of what, and you can change that using buttons in the Selection Tool Control Bar.
* There is a button on the right of the Tool Control Bar to determine if stretching an object changes line thickness or not.

## Shapes
* Circles: Tool Control Bar can give you partial circles.
* Squares: Tool Control Bar can give you rounded edges.
* Stars and polygons are nice. Squiggles??
* You can add bitmap images.

## Making paths
* To make a simple line, click and drag with left, release, then click right. <!-- Why so complicated? It's so we can make beautiful curves with the same tool. -->
* To make a Bezier curve, click and drag with left, release, then move mouse and click right to finalize line.
* To make a more complex curve, you can use the pencil tool with simplification.
* To make an area, bound it with objects and then use the paint dump tool.
* Tracing a bitmap is a great way to cheat!

## Modifying paths
* Add and delete control nodes. Change from a smooth node to a corner node and back.
* Simplify a path with Control-L.
* Do not be afraid!

## Fill and stroke
* Change object properties with Fill and Stroke, such as stroke width and other line characteristics.
* Make ends meet pleasantly by using butt ends for your lines.
* Arrowheads can be added as Markers.

## Colors
* Click to select fill color from little boxes, shift-click to select stroke color.
* Can have finer grained control using fill and stroke dialog (suggestion: use HSL, not RGB!)
* Use color dropper to change color using an existing color.
* To look super pro, use Colorbrewer colors.
* To look even pro-er, use gradients.

## Alignment
* Control-shift-A, and try options.
* Note the "Relative to" menu!
* Aligning text is different than lining up objects: use the special text alignment buttons.

## Groups
* Group with Control-G.
* Ungroup with Control-U.
* Group things to ensure consistent resizing and rotating across several objects.
* You can group groups, etc!

## Text
* Text is self-explanatory, except that clicking and dragging the text tool will make a nice text box that does line wrapping.
* Setting the default font in "Text and Font" menu item is very handy.

## Document
* Resize your document using document properties (Control-Shift-D).
* You can use the same dialog to export your document to a bitmap format.
* If you want to make sure that your document looks good on others' computers, you could consider converting text to paths.

<!--
## Advanced techniques:
* finding something by color
-->
