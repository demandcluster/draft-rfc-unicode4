# draft-rfc-unicode4
Draft RFC for unicode⁴ᴰ

## Unicode Missing Modifiers

* Mirrors; left-right and up-down
* The 16 colors 0-15. (default pallete but end-user defined)
* Add 7 levels of intensity
  (darker1-darker3 and brighter1-brighter3)
  
* Add 2x11 depth levels for anaglyph perspective
* Have 16 skin tone colors
  (Its missing albino(whiteish),baked(blackish) and asian colors) 

But to draw 4D hebrew or emotions we need more space than a ~21-bit code set.


## draft-rfc-unicode4

Drawing any language and emoticons and music and human emotions in one encoding named unicode⁴ᴰ.

This converts charsets into standard glyph drawing sequences to form letters.

And converts the current fonts to line size,bezier curve offsets,distortion modifiers so they have never missing glyphs.

* Keep 7 bit ASCII for legacy and re-implement everything as strokes and modifiers like tone letters
* Draw all characters with shapes sequences
* Unicode code point is 16 bit only
* Unicode code point sequence starts with a base code point and may have up to 21 code point modifiers
  (So hard data size for one character is 22*16b=44 bytes or 22 words)

* Have defined limits on modifiers repeats like max; 1,2,3,4,5,6,7 per modifier group
* Have 4 types of virtual start offset/draw grids like; 7x9, 9x7, 7x7 and 8x8
* Make monospaced/bold/italic/shadow/underline/etc as modifiers
* Give musical symbols more timing extensions
* Redone all emoji with limited sets core draw commands and add color and attributes with modifiers

An emoji like ":)" used to be drawn by an ascii command chain, now days copy-pasting from 1853 binary 😀 images is preferred.

By replacing those with a few generic emoji faces(+male+female+robot) we can add attributes with modifiers like +hair,+color,+glasses,+grin,+facedots,etc and real emotion encoded as tones.


## Hardware 

To visualize one 4D character glyph we could use;

* Mirror horizontal
* Mirror vertical
* Anaglyph depth
* Musical tone expression or visualized as 2d or 3d movements by the renderer
  (Adds the time dimension to text characters.)

Keyboards and chat rooms will have text art and optional music or bouncing/rotating letters embedded in the messages.

The new keyboard is a drawing board, a latin G keystroke sends a sequence to draw, like G-code 🤔 for letters.