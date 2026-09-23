# IEEE LED Cube Board

KiCad design for one slice of the LED matrix cube that the University of Denver IEEE
chapter is building as a group project. Three daisy-chained 74HCT595 shift registers drive
24 MMBT3904 low-side switches, which gives eight RGB columns from a five-wire bus (CLK,
DATA, LATCH, BLANK, GND).

Write-up: https://nruth633.github.io/projects/ieee-cube.html

Open `ieee.kicad_pro` in KiCad 10.
