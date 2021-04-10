# tasf-task04-socialdistancedetection

This was my fourth task as a Computer Vision & IoT intern at The Sparks Foundation, in this task I had to implement a Social Distancing Violation Detection System, which I had already implemented before as self-learning project, my approach remains the same, I use YoloV4, a famous object detection model to detect people, then I use OpenCV to draw a bounding box over them and using centroids of these bounding boxes I calculate the pixelated distance between any two centroids and if the distance exceeds the thershold of 50 pixels (i.e less than 50 pixels) I count that towards as a violation.

Code files along with the trained weights and COCO names can be downloaded from the link below as GitHub does not allow file size to exceed 25MB.
https://drive.google.com/drive/folders/1B7PmxRSznL1OChfPmM6r5CP-e9FF2GIT?usp=sharing

Moreover a video demonstration of this can also be seen at: https://www.youtube.com/watch?v=JDd9QkSHjRg

Feel free to leave any comments down below
