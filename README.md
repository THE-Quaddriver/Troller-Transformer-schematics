# Troller-Transformer-schematics
As I fix old Troller 'Auto Pulse' transformers, I am 'tabbing out' a schematic on Tiny-CAD and posting for the world to use.

I have done first the 'Transamp 1', modernized it, fixed its weaknesses and added some suggested improvments in the jpeg file.

Next came the 'Momentum 1' which is a momentum circuit added to a Transamp1 and the 'auto pulse' is done a little differently.

I will create the list of subs as I go on, so far, EVERY part is COTS, from mouser or digikey.  Except for the Darlingtons 
(which I laid into a stash from mouser), all I had in stock.


Transistor subs:
Transamp1 Darlington (Q1) - it nota TIP120 or better, make it one.  5A handling, 65w dissipation is more than ok for a 1 amp unit
Momentum 1 Darlington (Q1) - I have found a BDW23A, this is a similar Vebo and Hfe to the TIP120, but its Pd is half.  Change to a
TIP120

Momentum 1 Q201, Q202 - 2N4401 - upgrade to KSC2383 for more power handling and higher voltage to resist track spikes
Momentum 1 Q203 - 2N4403 - upgrade to KSC1013 - same reasons.  All are cheap and the TO92L case tolerance is better than TO92

Either 1 amp unit:  the diode bridge is 4 1N4001 units.  These are 1 amp in a typical DO-41 case, you can go to beefier units
but you will need to drill the mount pads.  That is too much like work, just get a 1.5-2amp bridge from just about anywhere.
Since there is not DC accessory terminal on the 1 amp units, the only DC stress is any case lighting you add, or the locos.  So a MU lashup
can stress this.

In the Momentum 1, there are 2 additional 1N4001's in the momentum circuit, however the placement has the current at milliamps at best

Capacitor subs:
The momentum 1 has 'from factory' capacitors, upgrade both electrolytics from 25v to 35v and use modern units.  C203 the .022uf 50v should be
fine but track spikes from a flywheel loco being a generator over bad track/switches etc can spike higher and eventually damage the unit, you
COULD upgrade this to 100v.
