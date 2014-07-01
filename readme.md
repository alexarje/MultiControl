
MultiControl 
============

Use any standard game controller (or other Human Interface Device) as a multipurpose music controller. 

Version: 0.6.2   
Author: Alexander Refsum Jensenius   
Developed: 2003--2014   
Language: Max/MSP (Cycling '74)   
License: [CC-GNU GPL](http://www.gnu.org/licenses/gpl-2.0.html)
Download: [application](http://www.uio.no/english/research/groups/fourms/software/MultiControl/index.html) | [source code](https://github.com/alexarje/MultiControl)


Features
--------

- Easy to choose any general Human Interface Device (HID)
- Outputs data using either Open Sound Control (OSC) or MIDI
- Automatically detects which buttons, sliders or other functions are in use
- Automatic scaling to 0.-1. (OSC) or 0-127 (MIDI)
- Easy to choose desired output scaling 
- Optional data smoothing
- Store presets to xml-files 


## Initial setup

* Set the HI device (input) and MIDI device (output) even if it's already correct, sometimes it needs to be confirmed.
* Before you assign OSC or midi to your controls, first move all the buttons and knobs, because the controls will change places on the list.
* Set the CC #, channel, etc. by clicking on it and dragging it up and down.
* If the midi values only range from 0 to 1, set the midi range for each input used to the full range, 0-127 (the default midi scaling seems to be broken).
* You can mute a control by unchecking its OSC box or midi box.
* If you have problems with midi, try leaving OSC on even if you aren't using it.
* Store your changes to a preset, or else they will be lost.
* Save file to any directory.

## General use

* Launch MultiControl and open your file.
* Load your preset, just selecting it isn't enough.
* Click all the buttons and move all the knob/sticks several times. Use the full range of the knobs/sticks, so that MultiControl can automatically calibrate them.
* Launch the app that uses the OSC or midi, and fire away!

## To update the settings

* Make your changes.
* Store the preset or else the changes will be lost.
* Save the file.


## Thanks to

- All the users who commented and found bugs
- [Kite Giedraitis](http://www.TallKite.com) for contributing the usage manual
