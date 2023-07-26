# MasterThesis Supplement: Object Detection Demo

Welcome to the MasterThesis supplement repository! This space houses the demonstrations for an efficient object detection system. The detection mechanism targets ground truth objects (blue), car detections (green), cyclist detections (yellow), and pedestrian detections (cyan).

## Contents

These videos exhibit the results of the object detection processes across various scenarios. Detailed descriptions for each video are as follows:

* **video_1.mp4**: This video utilizes the network pre-trained on AVX (synthetic) and fine-tuned with 20% of the KITTI data set. The tests were carried out on the AVX synthetic data set.
  
* **video_2.mp4**: This video uses the AVX (synthetic) benchmark network and was tested on the same AVX synthetic data set.
  
* **video_3.mp4**: This video employs the network pre-trained on AVX (synthetic) and fine-tuned with a 20% KITTI data set. The testing was performed on the real-world KITTI data set.
  
* **video_4.mp4**: This video utilizes the KITTI benchmark network and was tested on the real-world KITTI data set.

Note: All videos are displayed at a frame rate of 0.5 frames per second for improved visualization, even though the LiDAR’s rotation rate of 10 Hz equates to an actual frame rate of 10 frames per second. Please note that the frames in video_3 and video_4 are not temporally consecutive.

## Synthetic Scene Visualization

For enhanced recall, a confidence threshold of 0.1 was set, which has resulted in numerous false positives.
