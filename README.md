# ⚠️ As of 11th August 2020, this repository has been deprecated and will not be maintained or updated anymore. It's left here just for historical reasons.

## KREYCRAFT
Main repository of Kreycraft project (RXT098)

## Motivation
This is how far from a Brno in a car based on oalley www.oalley.net/map/uhy this project should improve the range that i currently have for 30 mins, 1h, 3h, 5h, 7h, 10h, 11h, 12h where 8 hours of a travel is least comfortable assuming that distance between brno and bremen (8 hour and +- 30mins of travel) is 767km which would cost 22036CZK (967.18 USD) assuming fuel costing 28 CZK (1.23 USD) per litre of Diesel where comfortable cost is around 3000 CZK (131.68 USD) accounting for return cost.<br>
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
- Model building practice for aerodynamic testing || Computer simulation?
- Carbon fiber research
### Equipment 
TODO

Relevant: https://youtu.be/YBLVaABtQJw?list=PLO6tMbMVaApFnINcth7WbWrAscz9AWEun

## Organization
1) Start with the engine
2) Build a design assuming specs of an engine
3) Sanitization
4) raw hardware + software
5) small scale test
6) Full scale test

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
 
 ### Control over the airplane
 TODO - Blocked by Pilot licence for experience
 
Dual stick?

Single stick?
 
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

https://youtu.be/hcM5OokeBRc - Info about how autopilot works

https://en.wikipedia.org/wiki/Aircraft_design_process - Aircraft design process based on wiki

https://www.reddit.com/r/chess/comments/7eq3j9/please_dont_buy_the_hype_with_this_obsessive/ - Apparently relevant to plane building -> investigate

https://www.flightgear.org/ - Open-source flight simulator

https://www.youtube.com/watch?v=eNSN6qet1kE - Some guy buily a plane from wood and electric motors -> relevant?

https://www.youtube.com/watch?v=k5BivSNiH8s - *Don't eat the big one stupid* -> Sanity check your results

https://youtu.be/IaFolrcK2Lg - Budget planes
- Cessna 150 - 20K USD used
  - Is slow (103 kts)
  - Range: 300 NM
  - Fuel consumption: 5GPH
  - Useful load: 303 lbs
  - high-wing airplane
- Cessna 172 - 29K USD used
  - Range: 435 NM
  - Cruise speed: 115 kts
  - Useful load: 930 lbs
  - Fuel consumption: 8 GPH
  - Most used airplane for training
  - high-wing airplane
- Piper Cherokee - 25K USD used
  - Low-wing airplane
  - Range: 455 NM
  - Cruise speed: 110 kts (depends on the model)
  - Useful load: 900 lbs
  - Fuel consumption: 8 GPH
- Grumman AA1A - 18K USD used
  - Range: 350 NM
  - Cruise speed: 109 kts
  - Useful load: 1007 lbs
  - Fuel consumption: 6 GPH
- Sonex - 20~24K USD used
  - Experimental airplane, not certefied
  - Comes as kit
  - Range: 500 NM
  - Cruise speed: 113 kts
  - Useful load: 480 lbs
  - Fuel consumption: 4GPH
  
https://www.sonexaircraft.com/video-tips/ - Build tips

https://youtu.be/0vUhzxzuIdE - Reference on high-end airplanes
- Shark airplane
  - Rotax 912 engine
  - Cruise speed: 146 kts
  - Fuel consumption: 5gal/hr
  - Price: 151K USD
- Diamond Dart 450 - 3M USD
  - Cruise speed: 250 kts 
  - Engine: unknown
  
![](https://youtu.be/0vUhzxzuIdE?t=575)

https://youtu.be/RN6vGxyMcVU - Backwards wings, reference for failure/potential design?
- Bernoulli's principle is relevant for wing design
- Aerofoil - ?
- Backwards sweap wing is recommended(?) for transonic and supersonic speed.

https://dsa.cz/index.php/archiv-aktualit/146-tiskove-prohlaseni - Fatal crash of Enstrom 480
- Reason: Unknown: Investigation needed and design should be adapted.
- News: https://www.idnes.cz/hradec-kralove/zpravy/nehoda-vrtulnik-slavonov-nachodsko.A190322_094824_hradec-zpravy_klu
  - Suspects crash with a wild life -> Can we adapt design to be more robust in terms of crash with a wild life so that result of colusion wouldn't end up as fatal?
  
### Plane model references
https://youtu.be/OOW-gsL46ds - Foam for a **model** of airplanes

https://youtu.be/akoJ2zBwX1o - Hugeass model of an BOEING 747-400 => Few of these in my design will be probably required. Seems as terrible idea to take inspiration from since it seems to be fake clickbait 

https://youtu.be/3R5npPftLys - Reference for a failure
- https://youtu.be/3R5npPftLys?t=27 = Approaching angle and speed was too high, design of a model has to be adapted for this scenario
- https://youtu.be/3R5npPftLys?t=32 = Apparently model is built from pine wood -> might be a good material for a model that scales to a real thing.
- https://youtu.be/3R5npPftLys?t=46 = Apparently the design is very front heavy -> Models should be balanced
- https://youtu.be/3R5npPftLys?t=98 = Notice landing with a one wheel -> This model design seems to be more easier to controll -> investigate why

