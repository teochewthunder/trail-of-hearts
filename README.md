# Trail of Hearts
This turns your mouse cursor into a CSS Heart which leaves fading imprints of itself all over the screen.

Preparation:
1. The entire screen should be covered by a div element, whch acts as a placeholder.

How it works:
1. Hide the mouse cursor
2. Replace it with a CSS heart at the *x* and *y* co-ordinates of the invisible mouse cursor, appending it within the div element placeholder.
  - This should happen every time the mouse moves.
  - The CSS heart is animated and "beating", for added effect.
3. At a certain interval, delete those hearts from the div element placeholder.

*Note: Des not appear to work on large displays.*
