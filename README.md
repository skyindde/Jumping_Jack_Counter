# Jumping_Jack_Counter
count the number of jump during Jumping Jack Exercise


This is an application of computer vision for counting the number of jump during the jumping Jack exercise.

This is very simple code, very short one.

using pose module of mediapipe To get the pose.

the number of jump on the screeen can be reset just by tapping here on the shoulder.

The hand has to go full up and come down to add into the count.

if someone  Raises the hand but bring it till halfway and raise the hand again, it wont be counted.

We are actually calculating the angle Between arm and Body. which has to come down below 45 degrees and go beyong 135 degrees to be able to get included in the count

this application is a good counter to count the number of jumps effectively. though, the code has to be included with more constrains, in order to avoid thye scenarios for someone to cheat during the exercise.
