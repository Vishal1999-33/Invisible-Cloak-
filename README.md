# About 

In this project we try to make a cloak invisible with the help of OpenCV. The technique here used is just opposite to that of green screening. In green screening effect we remove the background but here we will remove the foreground frame.

# Steps that will be followed

1. Capture and store the background frame. (This will be done for few seconds)

2. Detect the red colored cloth using color detection and segmentation algorithm.

3. Segment out the red colored cloth by generating a mask. (used in code)

4. Generate the final augmented output to create a magical effect. (harry.avi)

For simplicity, here we will make a red colored cloth disappear. We can also make other color disappear by updating the corresponding HSV values.

# What is HSV?

1)**_H:Hue_** 

Hue is the color portion of the model, expressed as a number from 0 to 360 degrees:

- Red falls between 0 and 60 degrees.

- Yellow falls between 61 and 120 degrees.

- Green falls between 121–180 degrees.

- Cyan falls between 181–240 degrees.

- Blue falls between 241–300 degrees.

- Magenta falls between 301–360 degrees.

2)**_S:Saturation_**

Saturation describes the amount of grey in a particular color, from 0 to 100 percent. Reducing this component toward zero introduces more grey and produces a faded effect. Sometimes, saturation appears as a range from just 0–1, where 0 is grey, and 1 is a primary color.

3)**_V:Value_**

Value works in conjunction with saturation and describes the brightness or intensity of the color, from 0–100 percent, where 0 is completely black, and 100 is the brightest and reveals the most color.

