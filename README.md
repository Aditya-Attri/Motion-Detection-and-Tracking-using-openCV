# Motion-Detection-and-Tracking-using-openCV
Motion detection and tracking using OpenCV uses background subtraction to detect motion and contours to track moving object.

Python libraries required:
1. OpenCV
2. Pandas
3. Datetime

Analysing all windows:
1. Gray Frame:
   In grey pictures there is only one intensity value as compared to RGB image where three intensity values are present. There images are blur so that we can calculate intensity difference in grayscale easily.
   
2. Difference Frame:
   It shows the intensity difference of first frame to the current frame.

3. Threshold Frame:
   If intensity difference > 32, then pixel will be white in color.
   If intensity difference < 32, then pixel will be black in color.

4. Color Frame:
   Color images inside green contour as these particular objects are moving.
   
