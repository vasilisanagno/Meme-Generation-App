# Meme-Generation-App

An application in Python for portrait editing and meme creation. This application allows users to upload portrait images in various formats (png/jpeg/tiff) and customize them with a diverse set of filters for meme creation.

## Features

- **Portrait Image Support:**
  - Accepts portrait images in formats like png/jpeg/tiff, providing versatility for user uploads.

- **User-Friendly Interface:**
  - A user-friendly interface allows easy selection of filters for meme customization.

- **Save and Clear Canvas:**
  - Option to save the edited meme in jpeg format.
  - Clear canvas feature for trying different filters.

## Available Filters and Features

1. **Gaussian Blur Filter:**
   - Blurs the image using a Gaussian filter.

2. **Laplacian Filter:**
   - Applies a Laplacian filter to highlight edges in the image.

3. **Color Boosting:**
   - Enhances the colors in the image for a vibrant look.

4. **Sharpening Filter:**
   - Sharpens the image to bring out details.

5. **Sepia Filter:**
   - Adds a sepia tone to the image for a vintage effect.

6. **Box Blur Filter:**
   - Blurs the image using a box blur filter.

7. **Face Detection:**
   - Detects faces in the image.

8. **Meme Placement (Mask/Hat):**
   - Places a meme (mask or hat) from the `meme_assets` folder on detected faces.

9. **Eyes Detection:**
   - Detects eyes in the image.

10. **Meme Placement (Eye Mask/Glasses):**
    - Places a meme (eye mask or glasses) from the `meme_assets` folder on detected eyes.

## How It Works

1. Upload a portrait image.
2. Choose from a variety of filters and features for meme customization.
3. Save the meme in jpeg format or clear the canvas for further editing.

## Running the Notebook

To run the `Project.ipynb` notebook, make sure you have Python installed on your system. You'll also need to install the following dependencies:

- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Imageio](https://imageio.readthedocs.io/)
- [OpenCV (cv2)](https://opencv.org/)

You can install these dependencies using the following command and run the app:

```
pip install numpy matplotlib imageio opencv-python
jupyter notebook Project.ipynb
```
