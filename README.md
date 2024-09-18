# People-Counter-from-real-time-recorded-videos using opencv
counts the number of people coming in and going out in a real time/ recorded video

This program is designed to detect, track, and count the number of individuals entering and exiting a specified area based on a reference line. Implemented using the OpenCV library, the code is versatile and can be applied to both real-time and recorded video feeds. For the purpose of demonstration, recorded video footage was utilized for analysis. Additionally, a version of the code for real-time video processing via a Raspberry Pi camera is provided and commented for reference.

To achieve accurate results, various OpenCV techniques have been employed, including background subtraction, morphological filtering, binarization to eliminate shadows, as well as dilation and erosion. The system also maintains a log file to document the output, ensuring that data can be reviewed and referenced in the future.

Below is a sample output from the analysis:

![image](https://github.com/user-attachments/assets/57376353-6e04-4c77-95d8-33a6df0eeecb)
