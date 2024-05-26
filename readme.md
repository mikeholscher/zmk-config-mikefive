# mikefive, a Kailh PG1316S keyboard

Welcome to my repo about my mikefive keyboard! 

It's wireless and five millimeters thick. Here's a picture of it:

![](images/mikefive%20done2.jpg)

The keyboard above is completely custom designed around Kailh PG1316S switches. 
These switches I got unexpectedly offered by Kailh when ordering other stuff. 
They do not seem to be on shelves yet to buy. Read on to learn more.

## Where are the files?!

Sorry. You won't find files or info to build the keyboard yourself here, yet. 

You will only find the ZMK config files for the custom shield, my current keymap, and a custom json for [ZMK Keymap Editor](https://nickcoutsos.github.io/keymap-editor/). 
Most commits here will probably be me updating my keymap :)

Maybe I was a fool to show it to the world already, while I only built a single prototype. 
Because, like with most first prototypes, I found stuff that needs to be improved before other people start building. 
Next to that, another unexpected opportunity arose, which I will definitly scream from the rooftops about when it's more concrete...

## Devlog

Find all noteworthy project developments here. 

I will update this page when there is news, and post on r/ergomechkeyboards too.

### 2024-05-26
I received a message from someone that was able to order some switches, and asked if I could share the footprint. The KiCad 8.0 footprint is in the [files folder](/files), and looks like this:

![](images/PG1316S_footprint_mikeholscher.png)

Some explanation:
- The outer, biggest square is the 16x16mm keycap.
- The slighty smaller square is the switch 'frame' size.
- The two small circles are holes for the allignment pins on the switch.
- Pads 1 and 2 are the switch pads.
- Pads 3 are the SMD mounting points for the switch frame. NOTE: I placed vias in these pads in the PCB to give the switch a more secure connection to the PCB. (I hope) this way the switch connects to both sides of the PCB instead of only the top layer. I connected all pads 3 to GND in the switch diagram and schematic.
- The weird shape in the top half is the available space under the switch for components. I placed my diodes there in the mikefive.

Kailh also made a [product page](https://www.kailhswitch.com/mechanical-keyboard-switches/kailh-ultra-thin-notebook-switch.html) for the PG1316S switch, including [spec sheet](https://www.kailhswitch.com/uploads/15927/files/CPG1316S01D02-data-sheet.pdf?rnd=569) where I based the footprint on. I did some further measurements on the physical switch to complete some details such as the space underneath.

### 2024-05-06 
kbd.news was kind enough to [repost](https://kbd.news/Mikefive-a-Kailh-PG1316S-keyboard-2366.html) my Reddit post on their website!


### 2024-04-28 
After completing the build on Wednesday 24th of April and working with it for a couple days, I decided to make a [post](https://www.reddit.com/r/ErgoMechKeyboards/comments/1cfg3vr/mikefive_a_kailh_pg1316_keyboard/) on r/ergomechkeyboards. 
It became a really long write-up, as I wanted to share as many details as possible.
Thank you all for your flattering replies! They really gave me energy to continue the project and make sure the keyboard will eventually get in the hands of people that want it.

