# Crimson Pro S

A slightly modified version of [Crimson
Pro](https://github.com/Fonthausen/Crimson).

Crimson Pro S differs from Crimson Pro in a few stylistic details: sharper
terminals, straight-legged capital R, slightly resized punctuation, recalibrated
weight distribution.

It's not better than the original Crimson Pro by @Fonthausen, it's just a little different.

![Waterfall Specimen](https://raw.githubusercontent.com/skosch/CrimsonProS/master/specimen/waterfall.png)

## Building the weight instances

Clone this directory, install [fontmake](https://github.com/googlei18n/fontmake)
(I recommend using a virtualenv), and run

```
fontmake -m CrimsonProS_Roman.designspace -o otf -a -i
```
and

```
fontmake -m CrimsonProS_Italic.designspace -o otf -a -i
```
