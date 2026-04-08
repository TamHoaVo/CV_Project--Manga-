# CV_Project-Manga
This project is a computer vision-based image colorization system that converts grayscale manga images into colored images using a deep learning model.

The model learns to map 1-channel grayscale images → 3-channel RGB images while preserving structure and boundaries from line art.

**Pipeline**
1.Load manga images using OpenCV
2.Convert images to grayscale (input) and RGB (target)
3.Resize and normalize images
4.Train U-Net model on paired data
5.Predict colors for unseen grayscale images

**Dependency**
Python
PyTorch
OpenCV (cv2)
NumPy / Matplotlib

