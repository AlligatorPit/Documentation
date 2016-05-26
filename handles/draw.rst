Draw
====
The Draw handle is used to render on the screen.

Text
----
Renders a string of text to the screen.

This function takes 5 arguments:

* ``String text`` - The text to render.
* ``Number x`` - The X coordinate to render at.
* ``Number y`` - The Y coordinate to render at.
* ``Number scale`` - The scale to render the text with.
* ``Color color`` - The color for the text. (This can also be a ``Number``)

Texture
-------
Renders a texture to the screen.

This function takes 6 arguments:

* ``Texture texture`` - The texture.
* ``Number x`` - The X coordinate to render at.
* ``Number y`` - The Y coordinate to render at.
* ``Number w`` - The destination width to render at.
* ``Number h`` - The destination height to render at.
* ``Color color`` - The color for the texture. (This can also be a ``Number``)

Rectangle
---------
Renders a colored rectangle to the screen.

This function takes 5 arguments:

* ``Number x`` - The X coordinate to render at.
* ``Number y`` - The Y coordinate to render at.
* ``Number w`` - The destination width to render at.
* ``Number h`` - The destination height to render at.
* ``Color color`` - The color for the rectangle. (This can also be a ``Number``)

Line
----
Renders a colored line to the screen.

This function takes 5 arguments:

* ``Number x1`` - The X coordinate for the first point.
* ``Number y1`` - The Y coordinate for the first point.
* ``Number x2`` - The X coordinate for the second point.
* ``Number y2`` - The Y coordinate for the second point.
* ``Color color`` - The color for the line. (This can also be a ``Number``)

Line3D
------
Renders a colored line to the screen with 3D projection.

This function takes 7 arguments:

* ``Number x1`` - The X coordinate for the first point.
* ``Number y1`` - The Y coordinate for the first point.
* ``Number z1`` - The Z coordinate for the first point.
* ``Number x2`` - The X coordinate for the second point.
* ``Number y2`` - The Y coordinate for the second point.
* ``Number z2`` - The Z coordinate for the second point.
* ``Color color`` - The color for the line. (This can also be a ``Number``)

GetScreenWidth
--------------
Returns a ``Number`` of the width of the draw port in pixels.

GetScreenHeight
---------------
Returns a ``Number`` of the height of the draw port in pixels.

GetAbsolutePoint
----------------
Returns the absolute screen point based on HUD element anchor as a ``Vector``.

This function takes 5 arguments:

* ``Number x`` - The X offset for the element.
* ``Number y`` - The Y offset for the element.
* ``Number w`` - The width of the element.
* ``Number h`` - The height of the element.
* ``Number anchor`` - The type of anchor as a number. This ranges between 0 and 16:
  * ``HEA_TopLeft = 0``
  * ``HEA_TopRight = 1``
  * ``HEA_BottomLeft = 2``
  * ``HEA_BottomRight = 3``
  * ``HEA_Left = 4``
  * ``HEA_Right = 5``
  * ``HEA_Top = 6``
  * ``HEA_Bottom = 7``
  * Types 8 through 15 (parented elements) are currently unsupported with this function.
  * ``HEA_Center = 16``
