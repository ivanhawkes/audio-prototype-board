# Audio Prototype Board

## Ideas

* Small PCB that can connect all the breadboard power and ground together.
	* This should fit nicely on the breadboard, try not to obscure slots, and have just one connector for power.
	* Power / GND connector in the centre, fans out to both sides.
	* Might need a negative voltage option for opamps.
	* Jumper to place power / GND on both sides, option to have different ones each side - need to experiment with opamps to see what makes sense here.
* Quick swap the pots somehow.
* Have these power options:
	* 9v, -9v, 18v, 12v, -12v, 5v, 3.3v
	* Do we need more than one pair of these at a time e.g. 9v and 3.3v? Seems likely for anything needing a pico / FPGA.
* Some easy access switches.
* Power LED indicators so we know what voltage levels are enabled.
* Ability to switch off some of the chips to stop phantom drain.
* I want it to work for general purpose projects e.g. pi pico work
* Audio probe access - gotta be easy to work back to front and front to back.
* Function generator input - might just be through AUX or hooking up TRS plugs to the generator - depends on ease of adding a typical 3.5mm audio jack. Be nice to have the square wave and the sine / triangle - so perhaps a stereo mini jack for this?
