# Gigrig G3 

## Setting Tuner

* Select preset
* Menu > Tuner > Tuner Enabled Mute Enabled

## Setting Tap Tempo

Turn sticky stomp off in order to access the preset first

Menu > Midi Out:
* Timefactor is on midi channel 2
* Pitchfactor is on midi channel 4

Both respond to CC+ and 01 and then 127

Turn stomp box mode on to make this active.  You will need to click on another preset and back onto the one you want.

## Setting a PC (Program Change) message to select a given preset on a pedal

Generally you would do the following:
* Midi > On > Midi Channel Number > PC+ > number of preset

On some pedals, e.g. the bloody Strymon Bigsky you need to select the bank then the preset

* Midi > On > Midi Channel Number > CC+ > 0 (bank)
* Midi > On > Midi Channel Number > PC+ > 0 (preset)

## OBNE MTET / Expression / Volume

To set the expression pedal to control the Octa Psi as a whammy...

* Deep Edit > Expr 1 Midi 1 > On, Channel 1, Heel 0, Toe 127, Control 3

Control:
* 01 - BigSky
* 02 - More or Less 
* 03 - Octa Psi
* 04 - Avalanche Run

To program the more or less to be a volume control:

Make sure you turn on the M.O.L and set the heel/toe accordingly, it's on (5)

* Deep Edit > Expr Midi 1 > ON > Channel 1 > Heel 000 > Toe 127 > Control 2

## Callibration and Curve

Click down to EXP 1 (or EXP 2 if you're using EXP 2!) cal heel > Click along > Now press your expression pedal so the heel is all the way back. > Press FootSwitch 4. G3 will display on the screen a percentage from 1 to 100% of how far the expression pedal travels.

Click FootSwitch 3 to go back, and click down to EXP 1 Cal Toe > Click along > Now press your expression pedal so the toe is all the way down. > Press FootSwitch 4. G3 will display on the screen a percentage from 1 to 100% of how far the expression pedal travels.

G3 will have now have calibrated the top and the bottom points of your expression pedal.

As well as this, if you click down lower to EXP 1 (or EXP 2 if you're using EXP 2!) log curve - you can now select tailored curves for your expression sweep. Click through these and try them out to work out what your preferred sweep is for your expression pedal.

## Volume Control

I don't know how the More or Less functions as above.  But to turn on volume pedal, set:

Exp Vol 1 - ON, then set Toe (o), Heel (100) 

and voila.

# Questions

When to use pre-gain and post-gain?

# General

* FX Enabled required for send/return
* Ensure you take the FX return output and then turn off all the FX Enabled and run it into the amp
