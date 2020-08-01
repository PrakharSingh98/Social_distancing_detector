# Social Distancing Detector
This uses the YOLO algoirthm pre-trained on the coco-dataset containing 80 differnt classes. It works on both live video(webcam) and recorded video files. <br>
Using the YOLO algorithm we segregate the person class in the video and draw bounding boxes after applying non-max suppression. <br>
Distance(Euclidien) between several bounding boxes is calculated and if this distance is less than threshold value, a beep sound is triggered and person is registered as voilating social distancing. <br>
It also shows the total number of people found and number of social distancing voilations. <br>
Just run the single jupyter file and follow the steps in comments.
### Requirements
OpenCV
