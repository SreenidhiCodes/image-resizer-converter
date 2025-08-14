# Task 7: Image Resizer Tool

# Objective
This project automates the process of resizing and converting images in batch using Python and the Pillow library. It can be run locally or in Google Colab, making it easy to process multiple images quickly.

# Tools & Libraries
-Python (3.x)
-Pillow – Python Imaging Library for image processing
-os – to handle file and folder operations
-Google Cola) – for  execution

# Folder Structure

│
├── app.py               
├── README.md            
├── input_images/          
├── output_images/        

 # Features

- Batch processes all images in a folder
- Supports multiple formats: JPG, PNG, BMP, GIF, TIFF, WebP
- Allows custom output size
- Option to change output format (e.g., PNG → JPEG)
✅ Works locally or in Google Colab


# Install dependencies:

pip install pillow

#  Usage
- Run Locally
- Place your images in the input_images/ folder.
- Edit the new_size and output_format in app.py if needed.

# Run the script:
- python app.py
- Resized images will be saved in the output_images/ folder.
-Run in Google Colab


# Supported Image Formats
.jpg, .jpeg,.png,.bmp,.tiff,.webp


# Example

Before: High-resolution 4000×3000 image (10 MB)
After: 800×600 image (300 KB) – quick to load, easy to share.
