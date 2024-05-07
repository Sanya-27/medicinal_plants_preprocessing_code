# medicinal_plants_preprocessing_code

# Overview:
This repository contains preprocessing code for identifying medical plants from images. The code preprocesses the images to enhance features for subsequent classification tasks. It includes basic preprocessing techniques, Contrast Limited Adaptive Histogram Equalization (CLAHE), and data augmentation.

# Features:
Basic Preprocessing: Resize, normalize, and enhance the quality of input images.
CLAHE: Apply Contrast Limited Adaptive Histogram Equalization to improve the contrast of images.
Data Augmentation: Augment the dataset with techniques such as rotation, flipping, and color adjustments.

# Dependencies
- Python 3.7 or higher
- OpenCV: Open Source Computer Vision Library for image processing tasks.
- NumPy: Fundamental package for numerical computing with Python.
- Matplotlib: Plotting library for creating visualizations in Python.
- scikit-image: Image processing library that includes various algorithms and utilities.
- Pillow: Python Imaging Library (PIL) fork, useful for image loading, manipulation, and processing.
- imgaug: Image augmentation library for generating augmented images for training machine learning models.
- TensorFlow or PyTorch: Deep learning frameworks that can be used for training image classification models.
- Pandas: Data manipulation library that can be used for organizing and analyzing image data.
- tqdm: Library for adding progress bars to Python code, useful for tracking progress during preprocessing tasks.
