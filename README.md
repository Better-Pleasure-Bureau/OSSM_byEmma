# OSSM_byEmma
Coding project for controlling the Open Source Sex Machine (OSSM) Emma has built.

Inputs:
2x 10k rotary potentiometers: https://www.rpelectronics.com/62-224-1-1-2-watt-with-1a-switch-10k-linear.html

1x Optical encoder: https://www.aliexpress.com/item/32892974727.html


- Knob 1 - sets stroke length
- Knob 2 - sets stroke speed
- Knob 3 - sets offset (probably encoder)


Outputs:
- Stroke length
- Stroke speed
- Oscillation midpoint/"Offset"


Project goals:
* Set an initial oscillation point to have strokes go back and forth from there. (default is strokes go back from max point)
* Be able to change stroke speed on the fly.
* Be able to change offset/oscillation point on the fly


Project plan:
* Set up non-interrupting state reading of knobs.
* Set up error handling (edges, overrides).
* Prepare for running premade programs


------

Resources:

Specs for the OSSM
https://kinkymakers.com/projects/open-source-sex-machine/
