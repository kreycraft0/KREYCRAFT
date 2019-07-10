# KREYCRAFT
Main repository of Kreycraft project (RXT098)

This project is **WORK IN PROGRESS**

## Motivation
This is how far from a Brno in a car based on oalley www.oalley.net/map/uhy this project should improve the range that i currently have for 30 mins, 1h, 3h, 5h, 7h, 10h, 11h, 12h where 8 hours of a travel is least comfortable assuming that distance between brno and bremen (8 hour and +- 30mins of travel) is 767km which would cost 22036CZK (967.18 USD) assuming fuel costing 28 CZK (1.23 USD) per litre of Diesel where comfortable cost is around 3000 CZK (131.68 USD) both ways.<br>
![](https://i.imgur.com/WSRk9U1.png)

## Abstract
Make an open-source design for an airplace and ways to construct it

Flying over atlantic in single engine plane is not recommended.(?)

Experimental planes are relevant

## Blockers
### Legal
- Flying licence
- Certification on mechanic (mandatory per 100h costs 900$ [verification needed])
- Certification on parts 
### Practical
- Hangar + Runway
- Electric motor research
- Power management research
- Model building practice for aerodynamic testing

## Perfect plane
### Software
- Running open-source software written in rustlang/c++ (high-performance programming lang in general) with community of maintainers and contributors 
- Software should be 'super strict' on any error message assuming that all parts of the place would be monitored in set interval and procedure.
- Should be running Linux kernel or ideally Redox Kernel
- Should allow plane to be driven remotely for testing.
- Should have on-board voice recognization
- Should have AI
  - AI has to be able to identify problems and apply solutions as they happend if it's able to fix them. 
- No binarry packages -> Everything should be compiled to achieve optimal optimization of software.

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
 - 1:10 model inside of a plane with ability to test results of possible outcomes in small scale?
 - Should have a place to sleep
 - Should have an air conditioner
 - Should have an air filter
 
 ### Maintainance
 - Maintainance should be done by me and software
 - All parts should have CAD model so that i would be able to make them on demand
 - This plane should be 0 cost maintanance as much as possible
 - Plane should generate a text log of events for diagnostics.
 - Everyone should be able to build the plane assuming required skillset -> More ppl using same design the most contributions it's gonna get -> less work for me with more effective outcome.
 
 ### Equipment
 - Should have all tools needed on board to work on a plane -> I should be able to fully dissassemble the plane with the tools from it (abstracted)

## References
Relevant https://www.youtube.com/watch?v=W9Uf-ynoDUE - Cessna is able to fly over Atlantic Ocean, but not made for it(?)

Relevant https://www.eaa.org - Association focused on building airplanes

https://www.bbc.com/news/world-africa-48914418 - Some ~~kid~~ teenager built a plane that flies, seems as terrible idea to take reference from since it seems to be fake and built as click bait.

https://youtu.be/iv_rRus-X9k?t=66 - Failure analitics of light sport airplanes, seems relevant.

### Plane model references
https://youtu.be/OOW-gsL46ds - Foam for a **model** of airplanes

https://youtu.be/akoJ2zBwX1o - Hugeass model of an BOEING 747-400 => Few of these in my design will be probably required. Seems as terrible idea to take inspiration from since it seems to be fake clickbait 

https://youtu.be/3R5npPftLys - Reference for a failure
- https://youtu.be/3R5npPftLys?t=27 = Approaching angle and speed was too high, design of a model has to be adapted for this scenario
- https://youtu.be/3R5npPftLys?t=32 = Apparently model is built from pine wood -> might be a good material for a model that scales to a real thing.
- https://youtu.be/3R5npPftLys?t=46 = Apparently the design is very front heavy -> Models should be balanced
- https://youtu.be/3R5npPftLys?t=98 = Notice landing with a one wheel -> This model design seems to be more easier to controll -> investigate why

