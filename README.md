# 4x MS20 KOSMO (ROUGH DRAFT)
This is a stackable but very crude MS20 filter based on the KS20 by Kassutronics

This has been tested and is working with some 100% neccesary changes

***The transitor footprints ended up backwords on Kicad.

Theres a few changes that are planned with this filter but it's up and working great atm. Everything is offboard wired from the PCBs. I drilled a custom alumunum panel and made some changes to the circuit.

The biggest change was the glaring backwords transistor footprints. This clearly will not work at all without those placed correctly. Then the cutoff, shape (lp/hp), the cv amount pots have the pad positions reversed (square pad is leg 3 not 1)
I updated the schematic and the Old gerbers to have the transitors placed correctly but double check.
I took out out r23 and added a 2k trimpot in place This adjusts the range of the throw
I changed r19 to a 47k. I was finding the CV range to be kind of dissapointing with  the original 100k.
It's not on the PCB but I added the trimpots for adjusting the scale and weight of the filter and connected the weight like a second cv knob with a trimpot and the scale adjusts the range
I also added a 6db/12db slope option like eddybergmans design https://www.eddybergman.com/2019/12/synthesizer-build-part-12-korg-ms20.html
The trimpots are in the schematic but for the 6db/12db option follow the schematic I'll update it in the future
The Ms20 new is for a future plan with using 90 degree headers and adding a jack panel and a pot panel with angled holes for the trimpots.
!!!theres no protection diodes on this circuit
for a single filter you may be able to get away without adding the trimpots but the variability in the filters are far too great.
I used bc558s instead of 557s like kassutronics also and I've heard you should match them but I didn't and it came out fine

The files I used are in the OLD folders and the new folders a future (probably a good bit from now) plan

The new PCBs will have a Panel, control PCB, jacks pcb, and 4 filter stacks on each. The resistor values will be where I found to like them. There will be 2 90 degree mounted adjustment trimpots. Switches for the 12db, 6db shelfs. 4 sets of 90 degree header pins to attach the pcbs to the main board. 1 filter knob, 2 dpdt (on/on) switches for the shelf (filters 1/2 and 3/4), 2 stereo pots (resonance 1/2 and 3/4) 4 cv level pots, 4 lp/hp mix pot, 4 drive pots, 4 input jacks, 4 output jacks and 4 cv jacks. All with no off board wiring (currently its around 100 wires) and removing the standoff holes and power header slots.
