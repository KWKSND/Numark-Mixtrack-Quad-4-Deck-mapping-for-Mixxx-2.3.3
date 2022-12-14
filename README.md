- Numark Mixtrack Quad 4 Deck Mapping and Script for Mixxx 2.3.3 Complex By DJ KWKSND
- Based on Mixxx default controller settings, Numark Mixtrack Mapping, and Numark Mixtrack Pro Script
-
- 1/11/2010 - v0.1 - Matteo <matteo@magm3.com>
- 5/18/2011 - Changed by James Ralston
- 05/26/2012 to 06/27/2012 - Changed by Darío José Freije <dario2004@gmail.com>
- 30/10/2014 Einar Alex - einar@gmail.com
- 08/14/2021-08/17/2021 - Edited by datlaunchystark (DJ LaunchStar) and added 4 deck support/LEDs... yeah
- 06/23/2022 by datlaunchystark on Mixxx 2.3.3 (mostly cleaned up code) https://github.com/datlaunchystark
- For the original code and the idea to get this controller functional in Mixxx. You guys are awesome! :)
-
- Updated on 12/6/2022 by DJ KWKSND (changed a bunch of code and mappings)
- https://github.com/KWKSND/Numark-Mixtrack-Quad-4-Deck-mapping-for-Mixxx-2.3.3
- I agree with the above statement
- You guys drove my O.C.D. crazy enough to get it done for everyone thanks for the inspiration
- I had not worked with midi or javascript, still more done in the last week or so than all you in 12 years ROFL
- I hope many people get to enjoy this wonderful controller for years to come without being robbed by VDJ
-
- Whats new?
-  There is now 2 versions of this script, Basic (the old easy controls), and Complex (as the manual describes)
-  Incorrectly mapped buttons were found and fixed
-  Samples S1 - S3 repeat as you tap the pad, S4 starts / stops the sample, great for drum loops set on repeat
-  FX123 & Filter knob speed is fixed
-  Pressing F123R when in Slip Mode will perform a momentary 1/16, 1/8, 1/4 or 1/2  beat loop roll
-  Pressing shift + FX123R pads now auto create a loop 1, 2, 4 or 16 beats in length at the play position
-  Pressing shift + turning FX123 knobs now change what effects are assigned to the pads
-  Pressing shift + turning FXF knobs now mix the dry / wet level of the FX123 unit
-  Pressing shift + keylock now enables / disables keylock
-  Pressing shift + keylock while in scratch mode now enables / disables slip mode
-  Pressing shift + scratch now enables / disables slip mode
-  Pressing shift + range now scales the range of the pitch slider
-  Pressing shift + delete in hot cue mode now enables delete mode to delete the hot cues
-  Pressing left shift + right shift now enables / disables AutoDJ (option, preference, AutoDJ, add random tracks)
-  AutoDJ now auto enabled with nice slow fade in when Mixxx starts so you can start Mixxx and walk away
-  Soft takeover added to all sliders and knobs, so there is no more extreme jumps in volumes or filters etc
-  Jogwheel direction when not in scratch mode was wrong now fixed
-  Fixed some timer kill errors
-  New colors on most pads
-  Hot cue LEDs now match the colors in the app (IMPORTANT use Recordbox hot cue colors to match this script)
-  Beautiful LED intro on Mixxx startup
-  Idle mode added to keep the LED show going until you start DJing, also now resumes if idle again
-  Improved controls and LED animation with scratching especially in reverse
-  LEDs now work with scratching and stop with end of track
-  Added master clipping indicators to the folder / file LEDs to keep you from blowing your shit up
-  Added channel clipping indicators to the headphone LEDs for each channel to prevent overdoing it on the EQ
-  Shutdown function added to turn off all possible LEDs with Mixxx app shutdown
-  Stutter flashes the BPM and Cue flashes to indicate 30 seconds from end of track
-  And finally i get to announce all jogwheel LEDs now work without having to press play on the controller :D
-  Hit play on the controller, or with the mouse on the Mixxx app, or let AutoDJ do it for you it all works YES!!!
-
- Features:
-  Supports 4 decks
-  Library browse knob + load A/B
-  Channel volume, cross fader, cue gain / mix, master gain, filters, pitch and pitch bend
-  Scratch / CD mode toggle
-  Headphone output toggle
-  Samples (Using 16 samples)
-  Effects (Using 4 effect units)
-  Cue 1-4 adds hot cues from play position
-  Loops:
-   Loop in 	(anywhere, after loop out is set hold to move with the play position, quantize to snap to the beats)
-   Loop out 	(anywhere, after loop out is set hold to move with the play position, quantize to snap to the beats)
-   Reloop 	(reloop from loop in point, press again to exit the loop)
-   Loop 1/2X	(1/2X the loop size until 1/32, then exit the loop, shift + 1/2X doubles the loop size)
-
- Known feature with all midi devices:
-  Each slide / knob needs to be moved on Mixxx startup to match levels with the Mixxx UI
-
- IMPORTANT, Set up Mixxx to work with this script:
-  Use Recordbox hot cue colors to match this script or you will have missing colors on some pads
-  Set autoDJ to add random tracks when low on remaining tracks so it never runs out of tracks on startup


https://user-images.githubusercontent.com/33409134/206051970-442262ff-fbdc-4e64-b608-6db78af59a30.mp4
