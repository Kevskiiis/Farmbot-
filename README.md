# Farmbot

### Project Description:
The college faced a challenge with agricultural students needing to repeatedly perform the repetative task of planting seeds in rows and columns on a tray. Inspired by technology, our student group developed a solution: a __farmbot__ that automates seed planting and watering, reducing the repetitive task so that energy could be placed elsewhere. 

### How it runs:
The farmbot operates on a board supported by Marlin firmware, which allows us to create instructions using G-Code, a programming language commonly used in Computer Numerical Control (CNC) machines. The program created for the farmbot sends instructions to servo motors that maneuver the farmbot’s head along the working x and y axes. Additionally, there is a servo motor on the head that works along the z axis, enabling it to get low enough to plant and water seeds.

An electric water valve attached to the head allows the flow of water upon instruction from the program. The head also features a vacuum system that uses suction power to pick up a seed and drop it at the designated spot.

When the G-Code is executed, the process begins by picking up a seed from a seed tray using the vacuum. The head then moves to the designated spot, lowers to drop off the seed, opens the water valve to water the seed, and finally, rises to return for the next seed. This repetitive task continues until the entire tray is finished.

### Images of Project: 
