---
title: Toolhead
layout: home
parent: Build
nav_order: 9
---


<h1>Hardware assembly guide</h1>
<h3>This page guides through the process of wiring up an skr pico to the bambu labs a1.</h3>

<h2>Motor Wiring</h2>
<h3>1. X Motor
<br>Start by removing the live camera and all th
<br>
<br>
<br>
</h3>








<h2>Toolhead Wiring</h2>
<h3>1. Start by unplugging all conectors from the toolhead board.<h3>
<image src="Images/Hardware/toolhead_board_removal_1.jpg">
<image src="Images/Hardware/toolhead_board_removal_2.jpg">
<h5>Source: Bambu Labs Wiki</h5>

<h3>2. Prepare the cables.
<br>The cables that are required are as follows:
<br>insert image of as follows,
<br>jst xh 4 pin female to male
<br>jst xh 4 pin male, to on other end, jst xh 2, and jst xh 3,
<br>jst xh 5 pin male, to other end, jst xh 5,
<br>Jst xh 2 pin, for thermister
<br>jst xh 2 pin for hotend.
<br>And take out the hotend, solder on wires and jst xh x 2 for the hotend and thermister
</h3>


<h3>3. Route the Cables.
<br><b>You can use a nylon sleeve around the wires to keep them safe, if so, plug the connectors into the toolhead, then route them through, then finally plug them into the skr pico</b>
<br>Plug in the cables into the parts, the motor cable goes from the extruder motor to the port on skr pico
<br>Plug in the fan0 connector into the part cooling fan (jst xh x4), and plug the other end, one into fan0 (?) port on skr pico, the other into an empty endstop connector (only for gnd)
<br>Plug in fan1 (exf) connector into the extruder fan (jst xh x5), and plug the other end into the lazer port near the fans (?)
<br>Connect the thermister and hotend wires to their respective areas, and <b>DO NOT PLUG THE THERMISTER INTO THE HOTEND PORT, IT WILL COOK IT AND YOU WILL BE SAD<b>
<br>Try and put some tape over the filament sensor ribbon cable, and eddy sensor leads to not cause a short.
<br>Get the printed toolhead cover from before and place it on, route the btt microprobe cables around and wire it up to the probe and servo ports. And put a jumper connecting the P_2 and Probe pins together.
<br>Nows your time to check the connection in the next step, then afterwards route it through a nylon sleeve if needed.
</h3>

<h3>4. Sanity Check.
<br> Empty,
</h3>



----
