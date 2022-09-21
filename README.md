# [Hardware] K80-Microcomputer
The K80 is a micocomputer built as if it existed in the 1970's. It uses a Z80A CPU clocked at 4Mhz, and has 4kB of RAM. In its first iteration the computer's display output was a charachter LCD (first a 16x2 lcd then a 20x4 lcd). This was meant to emulate the "dumb terminal" displays used in the 1970's for computer output. In its current iteration however, this display has been replaced with full composite video output. It operates at a resolution of 96x240 (streched to the aspect ratio of the monitor) with monochrome colour and it is a full bitmap display. This video signal is generated entirely by the CPU using software routines to bitbag the output.

## Version 1: LCD Display
![LCD_TEST](https://user-images.githubusercontent.com/17792367/191576277-92f977a0-6866-47a4-9535-6a88f935298b.jpg)

## Version 2: Composite Video Output
![COMP_CURRENT](https://user-images.githubusercontent.com/17792367/191576499-ed1e3967-9f0a-4957-93bd-0ffd5e7d0269.jpg)

## Version 2: Examples of Video Output
![COMP_VID](https://user-images.githubusercontent.com/17792367/191576576-2ec874b1-c352-44a2-8cea-87b4376c11f1.jpg)
![COMP](https://user-images.githubusercontent.com/17792367/191576592-5205238a-f7ed-4a2c-bd4b-ba26d3470998.jpg)

## Block Diagram
![k80](https://user-images.githubusercontent.com/17792367/185026366-2913677f-825f-465a-ad1e-28dea7704c86.PNG)
