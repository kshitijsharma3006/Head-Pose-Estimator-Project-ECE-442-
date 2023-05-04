# Head-Pose-Estimator-Project-ECE-442-

Head Pose Estimation

This project is an implementation of head pose estimation on the Atlas200 DK for determining a person's viewing direction. The head pose estimation can be useful in various applications, such as monitoring drivers' behavior in an automated driver assistance system or online exam monitoring.

The project first detects a face region in the input image and then uses the cropped region of the detected face as input to the head pose estimation model. The head pose is calculated in terms of three angles: yaw, pitch, and roll in an image.

The models for face detection and head pose estimation are pre-trained models provided in the Caffe framework. The models were converted to an offline model for inference on the board using the Ascend Tensor Compiler (ATC).
