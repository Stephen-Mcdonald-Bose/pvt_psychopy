# pvt_psychopy
Psychomotor Vigilance Test (PVT) using PsychoPy
===============================================
This test uses reaction time and vigilance to measure the sleepiness of the subject. 

## Instructions
Watch the red square on the screen. When yellow digits appear in the square tap on the space bar as quickly as you can. The digits will display the number of milli*seconds it took you to respond. 

## To-do
* Warn the user if the reaction time is < 100mSec. It will be counted as a false start.
* Stop the timer after 30 seconds if they haven't pressed a button.
* User should be warned to release the button and the test paused until that is done.
* record button release * if longer then 3 sec then don't use in analysis
* For user, input ID# instead of name. Maybe use face recognition to fill in ID#?
* Research has been done on PVT tests from 3 to 10 minutes. Let the user choose which time.
* Adjust the fixation point and feedback to be isoluminant. This will make it more useful to use pupillometry as another way of measuring sleepiness.
* switch to a button with better timing than the keyboard.

## Reference
Basner, Mathias, and David F. Dinges. "Maximizing sensitivity of the psychomotor vigilance test (PVT) to sleep loss." Sleep 34, no. 5 (2011): 581*591.
