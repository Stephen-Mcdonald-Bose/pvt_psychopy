# pvt_psychopy
Psychomotor Vigilance Test (PVT) using PsychoPy
===============================================
This test uses reaction time and vigilance to measure the sleepiness of the subject. 

## Instructions
Watch the red square on the screen. When yellow digits appear tap on the space bar as quickly as you can. The digits will display the number of milli-seconds it took you to respond. 

If you hit the space bar too soon, FS! (False Start) will be displayed instead of the time. 

If you take too long to hit the space bar, a tone will play and OVERRUN will be displayed.

## To-do
* Is the necessary data being written to the log file?
* User should be warned to release the button and the test paused until that is done.
* record button release * if longer then 3 sec then don't use in analysis
* For user, input ID# instead of name. Maybe use face recognition to fill in ID#?
* Research has been done on PVT tests from 3 to 10 minutes. Let the user choose which time.
* Adjust the fixation point and feedback to be isoluminant. This will make it more useful to use pupillometry as another way of measuring sleepiness.
* switch to a button with better timing than the keyboard.

## References
Basner, Mathias, and David F. Dinges. "Maximizing sensitivity of the psychomotor vigilance test (PVT) to sleep loss." Sleep 34, no. 5 (2011): 581*591.

Basner, Mathias, Daniel Mollicone, and David F. Dinges. "Validity and sensitivity of a brief psychomotor vigilance test (PVT-B) to total and partial sleep deprivation." Acta astronautica 69, no. 11-12 (2011): 949-959.
