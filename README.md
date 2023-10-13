
![rmk-wide-1](https://i.imgur.com/qOqRzdE.jpg)

# r/mk keyboard

The r/mk is a "keyboard" that mimics the style of the r/mk stickers that are floating around out there.

I got the idea of using plate mount MX stabalizers to go with the Choc v2 switch from Gimbal in this post:
https://www.keebtalk.com/t/new-kailh-choc-v2-switches/8349/22

If you use MX switches, you will need to use a plate with plate mount stabs, or skip the stabs altogether.

The switch footprints are from this project: https://github.com/luke-schutt/Pi5Keyboard. They support Kailh Choc V1, V2, Gateron low profile, and MX switches

And finally, the schematic and wiring for the rp2040 was taken from this project: https://github.com/Sleepdealr/RP2040-designguide

## Layout and pics

[Keyboard Layout Editor (KLE) link](http://www.keyboard-layout-editor.com/#/gists/66ec27985efc342d9c4acf2d43243eb4)

[Image gallery](https://imgur.com/a/in2jYlU)
## Stabalizer installation for Choc v2 switches

The installation of the stab wire is a bit tricky since it needs to go under the PCB.  This is the procedure I followed.

First, snap the stabalizer housing into the PCB without the stem or wire assembled.

<img width="600" src="https://i.imgur.com/YW99bD5.jpg" />

Next, insert the stems into the housing.

<img width="600" src="https://i.imgur.com/I2PKMe1.jpg" />

Finally, you'll need to squeeze the wire in between the PCB and plastic "clip" so that it can be pushed into place.  You may need to lift the clip with a flat tool to create a gap, and apply a bit of force to get the wire in place.

<img width="600" src="https://i.imgur.com/EMYdYsk.jpg" />

## Case assembly

| Part                        | Count | Notes |
|-----------------------------|-------|-------|
| 3mm acrylic                 | 6     |
| Acrylic cement              | 1     | [Link](https://a.co/d/a8NEyjm)
| 1.5mm double-sided foam tape| 1     |
| Thin double-sided tape      | 1     | [Link](https://a.co/d/aWlYKNr)
| Adhesive rubber feet        | 4     | [Link](https://www.etsy.com/listing/1327182543/vath-self-adhesive-silicone-rubber-feet)

The case featured in the photo is made of 6 layers of 3mm acrylic glued together.  You'll need to cut all 6 layers numbered #1 through #6 in the `case.ai` Illustrator file in the `assets` folder.  I used Choc v2 low profile switches for this build, but if you use taller switches (ex Cherry MX), you may want to add an extra `#2 Top spacer` layer to hide the gap.

1) Glue layers #1 through #5 together with acrylic glue of your choice (I use Weld-On).  
2) Cut 2 squares of foam tape and place them on the PCB where the corner blockers are.  Make sure the tape is completely hidden by the blockers.
3) Stick the PCB to the top of the case, pushing down on the area where the foam tape is.
4) Cut strips of the thin double sided tape and place them around the bottom edge of the case.
5) Line up the bottom layer (#6) and press it into place.
6) Place the rubber feet in each corner of the bottom of the case.
