# Computer Vision (COMP415)

### Assignment 1: Image Filtering and Edge Detection

#### Overview:
Implement image processing techniques using Python and OpenCV to handle image filtering and edge detection. 

#### Tasks:
1. **Image Acquisition**: Capture two images of a household object from different viewpoints.
2. **Convert to Grayscale**: Convert images to grayscale by averaging RGB values.
3. **Gaussian Smoothing**: Apply Gaussian smoothing with 5x5 and 11x11 kernels.
4. **Compute Image Gradients**: Use horizontal and vertical Sobel filters.
5. **Edge Magnitude and Orientation**: Calculate and display using a colormap.
6. **Canny Edge Detection**: Implement using OpenCV.

### Assignment 2: Feature Extraction

#### Overview:
Explore feature extraction techniques including Harris Corner Detection and Scale-Invariant Feature Transform (SIFT).

#### Tasks:
1. **Harris Corner Detection**: Implement and apply to various images with adjustable thresholds.
2. **SIFT Features**: Verify SIFT feature invariance under image scaling and rotation.
3. **Image Stitching**: Stitch multiple images using SIFT and homography (RANSAC method).

### Assignment 3: Classifiers, Object Recognition

#### Overview:
Utilize classifiers and object recognition methods to analyze images.

#### Tasks:
1. **CIFAR10 Classification**: Use SVM and Random Forest for image classification.
2. **Face Detection**: Implement EigenFaces and compare with Viola-Jones detector.

### Assignment 4: Neural Networks

#### Overview:
Develop and train neural networks for image classification and object detection.

#### Tasks:
1. **CNN for CIFAR-10 Classification**: Implement and train a shallow CNN.
2. **Advanced CNN with ResNet18**: Compare pre-trained and scratch-trained models.
3. **YOLOv8 Object Detection**: Apply YOLOv8 on a captured image of Montréal streets.

### Assignment 5: Segmentation

#### Overview:
Apply segmentation techniques using clustering and neural networks.

#### Tasks:
1. **Clustering for Segmentation**: Use K-Means and Mean-Shift on specific images.
2. **Neural Network Segmentation**: Implement Mask R-CNN and YOLOv8n-seg for detailed segmentation.

### Final Project: Dashcam Video Analysis

#### Overview:
Develop a Python program to analyze dashcam videos for vehicle and pedestrian activity.

#### Tasks:
1. **Video Analytics**: Count parked and moving cars, and pedestrians.
2. **Speed Calculation**: Compute the maximum speed of the dashcam car.
