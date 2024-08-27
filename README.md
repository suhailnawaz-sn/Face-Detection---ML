Description About Above Project 
I have Created This Project using Python and Open CV using Machine Learning Algorithms:

It initializes the webcam, detects faces, and draws rectangles around them. To add eye and mouth detection, you can follow these steps:

Load Eye and Mouth Haar Cascade Classifiers: Similar to how you loaded the face cascade classifier, load the pre-trained Haar cascade classifiers for eyes and mouths. You can find the XML files for these classifiers in OpenCV’s data directory.

Detect Eyes and Mouths: Inside the loop, after detecting faces, create regions of interest (ROIs) within the face rectangle for eyes and mouths. Then, use the eye and mouth cascade classifiers to detect eyes and mouths within these ROIs. Draw rectangles around the detected eyes and mouths.

Display the Result: Update the display window to show rectangles around detected eyes and mouths along with the face rectangles.
