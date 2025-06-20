# ZMK Miryoku-inspired firmware for the TOTEM keyboard

This is a ZMK firmware for a [TOTEM keyboard](https://github.com/GEIGEIGEIST/TOTEM).

The original keymap is copied from [BSAG's config](https://github.com/bsag/zmk-config-bsag), which in turn is based on both the great [Miryoku layout](https://github.com/manna-harbour/miryoku_zmk), and [urob's ZMK config](https://github.com/urob/zmk-config). At this point it is a bit difficult to say how much of the original configs is left. 

Some features and design choices:

- [ColemakDHm](https://colemakmods.github.io/mod-dh/) alpha layout.
- Alternate hand layout for most of the layers (so that the layer key and modifiers are on one hand, and the main keys of that layout on the other).
- Combine symbol layers with urob's idea of having symbols as combos. 
- "Timer-less home row mods", which work really well and avoid the usual drawbacks of home row mods.
- Caps word, which is activated by tapping both home row index finger keys.

- Having all the mods in the home row makes it pretty easy to mash a bunch of them to get Hyper (Shift + Command + Option + Control) or Meh (Shift + Option + Control), but --- just because I can --- the index and middle finger keys on the bottom row serve as Hyper and Meh mod taps too. That makes it very easy to create useful keyboard shortcuts for global OS use without any fear of clashes.

- Pressing any key wakes the Totem from soft sleep. 

