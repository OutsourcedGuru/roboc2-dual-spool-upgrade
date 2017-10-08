# roboc2-dual-spool-upgrade
Step-by-step instructions for upgrading the Robo C2 for dual filament spools.

![dsc_0062](https://user-images.githubusercontent.com/15971213/31312760-fb6478e4-ab80-11e7-8205-3bb1a719c46d.png)

## Overview

The Robo C2 printer is awesome in many ways. Its included spool holder, however, has a number of flaws in its design:

* The mounting hole for the spool holder is slightly too large for the included holders, resulting in the holder spinning inside the rectangular hole and sometimes falling out mid-print
* The included holder for 1KG spools really isn't up to the challenge of all that weight
* The holders, as supplied, often catch against Robo's own filament spools given the existing design
* The location of the existing spool holder is too high and too close to the bottom of the filament run-out switch assembly, exacerbating any cross-filament problems and especially with infused rolls

To work around these flaws, I've created a completely new design to accommodate two 1KG spools at once.

The new design includes ball bearings, moves the spool(s) lower, re-orients them so that they're more inline with the filament run-out switch assembly and has a safety feature which helps on Shaxon and other problematically-wound filament spools.

I've decided to create two versions of the holder to include a second *smaller* version to hold two half-KG of filament. The only real difference between the two in printed parts are the lengths of the sleeves and the Under-brackets. And obviously, they use slightly longer dowels. If you like making these, double the amount of ball bearings and bolts and you should be able to make both models easily with the same materials otherwise.

### Follow-up project
Soon enough, I plan to create an enclosure for this dual-spool assembly to keep both spools dry since I intend to print PVA on the second extruder.

## Parts required
I've included pictures below to make this easier.

### Parts to order/buy
* Four non-flanged ball bearings, 8mm ID x 22mm OD, around $1.99 per pair, for [example](https://www.servocity.com/8mm-id-x-22mm-od-non-flanged-ball-bearing)
* Two types of dowel
	* 7/8" x 36", around $3.59 each at arts & crafts stores, for [example](https://www.whiteheadindustrial.com/p-20143-78-x-36-hardwood-dowel-rod-code-brown-no-301621.aspx?gclid=EAIaIQobChMI3OTK_Mbf1gIVg2x-Ch3YIQa1EAYYASABEgJSA_D_BwE)
	* 3/16" x 36", around $0.79 each at arts & crafts stores, for [example](https://www.c2f.com/html/productdetail.asp?p=MID-7905)
* Several types of #6-32 shouldered aluminum bolts, around $1.69 for quantity 25 each for [example](https://www.servocity.com/6-32-zinc-plated-socket-head-machine-screws), or something like [this](https://www.servocity.com/actobotics-hardware-pack-a) would be a better idea
	* 7/16" (11.11mm) @ four each
	* 1/2" (12.72mm) @ four each
	* 1/4" (6.35) @ two each
* Four or eight soft furniture stick-ons for the bottom
* Superglue to connect the two bottom brackets together
* Clamps (two) of some kind
* A strong rubberband to hold things while they're being glued
* A 7/64ths hex wrench for tightening all the bolts
* A hammer
* A pocketknife or similar
* A wood or hack saw

![ball-bearings](https://user-images.githubusercontent.com/15971213/31312441-2de79994-ab78-11e7-87bb-4fae43f5bfde.jpg)

![dowel_7-8ths-inch-x-36-inch](https://user-images.githubusercontent.com/15971213/31312303-14409c4c-ab74-11e7-89db-7680761c5c75.jpg)

![dowel_3-16ths-inch-x-36-inch](https://user-images.githubusercontent.com/15971213/31312334-fd806b94-ab74-11e7-9c21-cce35a57c1b4.jpg)

![bolt-6-32_7-16ths](https://user-images.githubusercontent.com/15971213/31312413-5cf2db64-ab77-11e7-942b-7443bf34e120.png)

![clamp](https://user-images.githubusercontent.com/15971213/31312409-3bb63b08-ab77-11e7-9c00-60d47c6c52df.jpg)

![hexkey-7-64ths](https://user-images.githubusercontent.com/15971213/31312430-b41754d8-ab77-11e7-8bd8-0a58fb8784d0.jpg)

### Parts to print
Here's the part list, all in PLA. I used the standard [Robo 3D Jet Black](http://robo.fyi/consumables/filament-by-type-by-vendor) for all the parts.

#### Note
Given that the Robo C2 has a fair degree of inaccuracy when printing Z-oriented holes, it's important for you to print these parts using the GCODE I've provided; otherwise, your bolts won't fit. (I've already factored in the hole-shrinkage in this dimension.)

* Assembly x 2
* End Cap x 4
* Mid-shim x 2 (needs raft & support)
* Sleeve x 4 *{Note that there is a shorter pair for the half-KG version of this project so choose appropriately}*
* Center Axis Bracket x 2
* Center Axis Cover x 2
* Under-bracket (both halves) x 2 *{Note that there is a shorter pair for the half-KG version of this project so choose appropriately}*

## Installation
After printing all the parts, here are the assembly instructions.

1. Do a test-fit to determine if the **End Caps** fit into the ball bearings; that the 3/16" dowel fits inside the **Sleeves**, **End Caps** and **Mid-shims**; that the #6-32 bolts fit into the threaded holes and fit through the clean ones
2. Use the pocketknife to clean the upper half of the ball bearing slots in both **Assembly** parts
3. Insert one ball bearing each into the related slots in both **Assembly** parts, use a spare raft or other thin plastic part on top of this and use the hammer to gently force them into the back of each hole
4. Add one **End Cap** to each ball bearing
5. Insert the 3/16" dowel into one of the **End Cap** & ball bearing combinations
6. Onto this, thread in this order: one **Sleeve**, one **Mid-shim**, another **Sleeve** and another **End Cap** (with the opposite orientation as the last)
7. Pushing everything together, mark the point where the dowel clears the last part and cut the dowel
8. Repeat for the other ball bearing
9. Sandwich everything together with another **Assembly** part on the opposite side
10. Flip everything upside-down and begin attaching the **Under-bracket** halves using the four 1/2" bolts... carefully use the hammer to set the **Assembly** parts evenly into the rectangular groove in the **Under-bracket** parts, tighten each bolt firmly
11. Add the strong rubber band to hold together both **Assembly** parts and everything in between
12. Verify that all four sleeves spin freely
13. Use the two clamps to hold the **Under-bracket** halves in place
14. Apply the glue carefully, making sure that there's something under your project to catch any drips (it's probably best to let it sit overnight)
15. Remove the clamps and rubberband
16. Add four cushioned furniture bumpers/feet to the bottom to protect your table top
17. Use the 1/4" bolts to attach one each **Center Axis Cover** to the **Center Axis Brackets** (don't over-tighten)
18. Use two each 7/16" bolts to attach both **Center Axis Brackets** to their respective Assembly part, tightening them firmly
19. Close one **Center Axis Cover**, insert the 7/16" dowel through everything and mark a line 2mm inside (the depth of the other **Center Axis Cover**), saw through the dowel
20. Orient the dual-spool holder behind the printer and add two filament spools so that the filament spools clockwise as seen from the right side of the printer, slide the dowel through the middle and close both covers, slightly tightening their bolts by hand

![testfit](https://user-images.githubusercontent.com/15971213/31319791-186148a8-ac1e-11e7-8fac-703bc07e2deb.jpg)

![bottomaxles](https://user-images.githubusercontent.com/15971213/31319765-bff173c8-ac1d-11e7-8bd5-8b0531d0e797.jpg)

![dsc_0065](https://user-images.githubusercontent.com/15971213/31312792-5ab462e0-ab82-11e7-8a47-0ffae162bfc6.png)

![dsc_0064](https://user-images.githubusercontent.com/15971213/31312804-b3b9a634-ab82-11e7-95fc-6ed904aea4f6.png)

![dsc_0063](https://user-images.githubusercontent.com/15971213/31312773-912cab62-ab81-11e7-865d-13fbc289d1a5.png)

![sideview-c2andholder](https://user-images.githubusercontent.com/15971213/31319572-b697381a-ac1a-11e7-9f3c-816dddbba648.png)
