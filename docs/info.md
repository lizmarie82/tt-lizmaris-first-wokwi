<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project is a combinational logic controller for a hydroponic system. The 8 DIP switches simulate sensor conditions such as low water level, high air temperature, abnormal pH/EC, high humidity, low light, high water temperature, and flow failure. Logic gates process these inputs and activate outputs for alarm, pump, fan, lighting, tank filling, nutrient warning, critical state, and normal operation.

## How to test

Run the simulation and toggle the 8 DIP switches to simulate different sensor conditions. A switch at 0 represents a normal condition and 1 represents an alert condition. Observe the output LED bar to verify the controller response. For example, 00000000 represents normal operation, 10000000 simulates low water level, and 00000001 simulates a flow failure.

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
