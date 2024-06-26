# SteganoVision

Stegano Vision is a Python-based application that allows users to hide and reveal secret text messages within image files using steganography. The project leverages the Tkinter library for the GUI, PIL (Pillow) for image handling, and Stegano for the steganography functionality.

## Features

- **Hide Secret Messages:** Encode text messages within image files using steganography.
- **Reveal Secret Messages:** Decode and reveal hidden text messages from steganographic images.
- **Save Encoded Images:** Save the images with hidden messages as new files.

## Prerequisites

Ensure you have the following installed before running Stegano Vision:

- Python 3.x
- Tkinter (comes pre-installed with Python)
- PIL (Python Imaging Library) or Pillow
- Stegano library

## Components

### `showimage()`
- Opens a file dialog to select an image file and displays it in the GUI.

### `Hide()`
- Hides the secret message within the selected image using the LSB (Least Significant Bit) steganography method.

### `Show()`
- Reveals the hidden message from the selected steganographic image.

### `save()`
- Saves the steganographic image with the hidden message as "hidden.png".

 This project provides a simple and effective way to demonstrate the principles of image steganography. Enjoy exploring the hidden messages with Stegano Vision!
