# Varmilo VB87M DIY

DIY project for the leftover Varmilo VB87M plastic case

![](https://i.imgur.com/v0MGNCtl.jpg)


## Plate

Mechanical keyboards need a "plate" it should be rather precise, preferably aluminum.

Stock plate (1.5mm steel):

![](https://i.imgur.com/PDPaO1yl.jpg)

I've used [KLE][1] and [Swillkb][2], with a standard TKL layout (with modified 0.5u distance to function keys).

Since there's no CNC or powerful lasers nearby I was trying to use low-power laser and cut plastics.

First batch was [unsuccessfull](https://imgur.com/a/HyMhu) (the laser was apparently a little off).

Maybe it would be easier just 3dprint everything, but it needs extra modelling.

I'm going to use Cherry-style stabilizers, so it's very important to have precisely 1.5mm plate.


## Electronics

I was going to use Arduino Pro Micro (because it's cheaper than Teensy) and handwire everything.

That's all before going fully wireless, of course.

There's lack of pins on that Pro Micro though (Teensy has 24 GPIO pins while Pro Micro only has 18).

It can be solved if you solder to leds, see https://hackaday.io/project/8282-alpen-clack/log/27395-matrix


[1]: http://www.keyboard-layout-editor.com
[2]: http://builder.swillkb.com
