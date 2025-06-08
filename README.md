This project aims to detect jersey numbers from images or video frames using OCR (Optical Character Recognition) techniques. We use Python with OpenCV and EasyOCR libraries to preprocess images, isolate regions of interest (ROI), and extract digit text from sports jersey images.

What We Did

Loaded images containing jersey numbers.
Applied image preprocessing steps including grayscale conversion and thresholding to enhance digit visibility.
Used EasyOCR to detect and read digits within the processed region.
Drew bounding boxes and confidence scores on detected numbers.
Tested and evaluated the system on sample images.
Current Status & Results

The system can detect single digits in relatively clear, well-lit images.
Detection accuracy depends heavily on image quality and ROI extraction precision.
Current success rate varies due to noise, lighting conditions, and occlusions.
OCR runs on CPU by default; GPU support can significantly speed up processing.
Challenges

Handling images with complex backgrounds and varying lighting.
Processing angled, blurry, or low-resolution jersey numbers.
Distinguishing digits when overlapping or partially obscured.
Potential Improvements

Enhance preprocessing by experimenting with adaptive thresholding, image sharpening, and noise reduction.
Improve ROI extraction using advanced contour detection or deep learning-based object detection models (e.g., YOLO, Faster R-CNN).
Train a custom OCR model tailored to jersey font styles and conditions.
Integrate GPU acceleration to boost OCR speed.
Test on larger, more diverse datasets for robustness.
