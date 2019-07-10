## Abstract
Make an open-source design for an airplace and ways to construct it

This is how far i can get in a car under 12 hours from a Brno  www.oalley.net/map/uhy

Flying over atlantic in single engine plane is not recommended.(?)

Experimental planes are relevant

## Perfect plane
### Software
- Running open-source software written in rustlang/c++ (high-performance programming lang in general) with community of maintainers and contributors 
- Software should be 'super strict' on any error message assuming that all parts of the place would be monitored in set interval and procedure.
- Should be running Linux kernel or ideally Redox Kernel
- Should allow plane to be driven remotely for testing.

### Hardware
- Design of the plane should be open-source and available to everyone to build a community around to get free QA and sanity checks + improvements.
- Expecting electric engine to cut down the cost of fuel and pollution
- Design should be sanitized -> If engine cuts off or halts the airplace should be able to safely glide down on a ground/float on the water with some options to dodge buildings etc..
- All parts should be indexed (have CAD to everything and exact specifications based on testing) and it's status monitored by a software to make sure that all parts are in working condition to avoid fatailities .
- optionally: solar panels on the top of the plane to passively charge, but i doubt it would be any good for overall range
- optionally: gas engine in case electric cuts off assuming that it fits in the maximmum weight of said design
- Radio should have a backup power and there should be backup of a radio so that i woudn't end up anywhere without radio contact.
- On screen display assuming that it will be optimized for a direct sunlight
- Some way of handling a batteries should be considered in case of a fire.
  - Eject them with a paraschute assuming that system recognizes plane beeing under said treshold?
  - Forcing environment around a pack that won't allow fire from beeing created and only melts the batteries untill pack is removed and safely 'stabilized'?
  - Making a custom battery pack that in case of failure burns in expected way that won't affect the airplane assuming situation where pack fails mid-air? 
  - Nuclear? Sounds crazy, but it might be a better alternative to lithium.

## References
Relevant https://www.youtube.com/watch?v=W9Uf-ynoDUE -> Cessna is able to fly over Atlantic Ocean, but not made for it(?)

Relevant https://www.eaa.org -> Association focused on building planes
