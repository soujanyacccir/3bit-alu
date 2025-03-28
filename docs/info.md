<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works


This design executes binary operations on two octal numbers encoded in an 8-bit instruction and outputs the result to the 7-segment display. The instruction is made up of 8 total bits.

## How to test

Examples:

0 0 1 0 0 0 0 1 -> ADD 4, 1 -> Displays 5 on 7-Segment Display

1 1 1 0 0 1 0 1 -> XOR 4, 5 -> Displays 1 on 7-Segment Display

1 0 1 0 0 1 0 1 -> AND 4, 5 -> Displays 4 on 7-Segment Display

0 1 1 1 0 1 0 1 -> OR 6, 5 -> Displays 7 on 7-Segment Display

0 0 1 0 1 1 1 0 -> ADD 5, 6 -> 7-Segment Display DP illuminated indicating overflow condition

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
NO
