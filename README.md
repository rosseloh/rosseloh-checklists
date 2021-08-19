## rosseloh-checklists
#### Custom-built PDF checklists for X-Plane addons, designed to fit nicely on Avitab with minimal fuss.
## Current Checklists:
* HotStart TBM900
* Leading Edge Simulations Saab 340A
* IXEG 737-300
* FlyJSim 737-200
* FlyJSim 727
* JRollon SF260

## What's the point?
In my humble opinion, too many sim pilots create "checklists" that they then share, which are far, FAR more than checklists. These pilots tend to create full procedure lists, including such lovely details as "hold key to START" which any pilot should eventually know how to do when they're told to "start the engine". And there's nothing wrong with these lists! But they're too wordy for my purposes - I want something I can use to actually check my work, after I've already done it - like the real pilots do. The normal after-start flow in a 737-300 includes connecting the engine generators to the bus, setting the ignition to continuous, setting the pressurization controller to Flight mode, turning off the APU bleed and the APU itself if not required, checking various systems for proper operation, and several other things that get very wordy when written down. The pilot and copilot just *do* these things, and use the after-start checklist to *check* that they have been done, not to tell them how to do it in the first place.

The design ideals at this moment are to create checklist files that are:
* Sized such that they fit on Avitab with no zooming or panning required
* A different page for every checklist, unless two are so closely related that it makes sense to have multiple per page - click the next page button to move on to the next checklist when finished.
* Simple and easy to follow, so long as the user understands the airplane they are flying. These are not full procedures, but *checklists*. They won't tell you where the de-icing panel is and which switches to flip, but merely ask "is the de-icing system set as required?"
* Have as little extraneous information as possible. Exceptions to this might be exemplified by the After Takeoff and Approach checklists including flap schedules or important speeds.
* Be easy to read quickly and visually distinct so a pilot can maintain their place with little mental effort.

The end result should be checklists that can be followed at a glance, with very little heads-down time during high-workload flight segments. The first few times a pilot uses one they may need to spend a little more time figuring out what they're doing, but that's the beauty of the simulator - we can take our time if necessary. Once the pilot is familiar with the aircraft, these checklists should be sufficient to ensure safe operation in as short of a time as possible.

## File organization

Each aircraft will have its own sub-directory, with two primary files per folder - a text file with the basic checklist items, and the actual PDF file which is sized appropriately to work with Avitab out of the box.

If you have a suggestion for new or modified items for the checklists, the text file is where to put those (or raise an issue, if that's your thing).
