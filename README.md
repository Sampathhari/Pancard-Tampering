# Pancard-Tampering
Project Title: PANCARD TAMPERING DETECTION PROJECT

Project Overview:
The project aims to assist various organizations in verifying the authenticity of the PAN cards submitted by their employees. It utilizes image processing techniques to calculate the structural similarity between an original PAN card and the one provided by the employees.

Project Description:
The project involves the following steps:

Loading original and user-provided images.
Converting the format of the original image to match the tampered image.
Resizing both images for consistency.
Displaying the original and tampered images.
Reading images using OpenCV.
Converting images to grayscale for simplicity in image processing.
Computing the Structural Similarity Index (SSIM) to determine the similarity between the original and tampered images.
Calculating threshold and contours to identify differences.
Drawing bounding rectangles around differing areas.
Displaying images with contours, difference, threshold, and bounding rectangles.
Skills Used:
Image Processing | Python Programming | OpenCV | PIL | Computer Vision

Tech Stack Used:
Python | OpenCV | PIL | scikit-image | imutils

Key Achievements:

Successfully implemented image processing techniques to detect tampering in PAN cards.
Calculated the Structural Similarity Index (SSIM) for image comparison.
Utilized OpenCV for image manipulation and contour detection.
Summary:
This project is applicable in various organizations where ID verification is crucial. It can be adapted for different ID types such as Aadhar, voter ID, etc., providing a reliable method to identify whether the submitted ID is original or potentially tampered with.
