# Camera Calibration Using Accelerometer
Recent mobile devices are mostly integrated with camera and accelerometer sensors. As long as the device is immobile, the accelerometer is affected just by gravity, hence the measured acceleration refers to gravity. On the other hand, synchronized captured images can also carry the direction of gravity information depending on the content of the scene. For instance, structures as buildings, lighting poles, furniture, walls, etc. can show the direction of gravity on the images. These vertical structures in the image can be used to detect the vanishing point indicating zenith. Hence, estimation of the camera internal parameters which map gravity vector into the vanishing point is possible. Based on this theory, in this work, we propose a novel camera calibration method which only requires taking photos of an arbitrary building and recording the synchronous acceleration vectors from an onboard accelerometer. Then, the vanishing points detected from the images and the acceleration vectors replace the 3D calibrator. The resulting camera calibration method has competitive results compared to the popular calibrator-based methods despite it does not need any external calibrator object. The proposed camera calibration method both has the convenience of self-calibration approaches, and gives highly competitive accuracy within calibrator-based approaches. 
## Instruction
1. Install CamAcc application on the device. 
2. Take around 20 photos of a building by roughly rotating the device one turn around the principal axis of the camera.
3. Transfer the files (images and recorded acceleration data) to the main folder.
4. Using the notebook, compute the vertical vanishing points for each image and estimate the camera parameters.
## Authors
- Okay Arık
- Seniha Esen Yüksel
## References
The camera calibration method in the notebook are based on the following paper. Please cite the paper when using this notebook in an academic publication.
- O. Arık and S. E. Yuksel, "Mobile Device Camera Calibration Using Building Images and Onboard Accelerometer," in IEEE Transactions on Instrumentation and Measurement, vol. 71, pp. 1-8, 2022, Art no. 5022208, doi: 10.1109/TIM.2022.3204309.
