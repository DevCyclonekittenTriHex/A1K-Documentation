---
title: Toolhead
layout: home
parent: Build
nav_order: 2
---


<h2>Toolhead Wiring</h2>
<h3>1. Start by unplugging all conectors from the toolhead board.<h3>
<image src="Images/Hardware/toolhead_board_removal_1.jpg">
<image src="Images/Hardware/toolhead_board_removal_2.jpg">
<h5>Source: Bambu Labs Wiki</h5>
----
<h3>2. Prepare the cables.</h3>
<h4>The cables that are required are as follows:
<br><b>All cables are 1 metre in length, and all the jst xh connectors have the tabs up.</b></h4>
<image src="Images/toolhead_cables.png">

</h3>
----

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
----
<h3>4. Sanity Check.
<br> Empty,
</h3>

----
