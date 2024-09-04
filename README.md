# Image Steganography

## Description

This Python application uses image steganography techniques to encode and decode hidden text within images. It provides a graphical user interface (GUI) using Tkinter, allowing users to select images, hide text, and retrieve hidden messages. The application supports PNG, JPEG, and JPG formats.

## Imports

This application requires the following Python libraries:

- `tkinter`: For creating the GUI components.
- `tkinter.filedialog`: For file selection dialogs.
- `PIL` (Pillow): For image manipulation and processing.
- `os`: For file and directory operations.
- `io`: For handling in-memory file operations.

You can install the necessary libraries using the following commands:


```bash
pip install pillow
```
The tkinter library is included with Python's standard library, so no additional installation is required for it.
## Usage

1. **Encoding Text in an Image**:
   - Select an image in which you want to hide text.
   - Enter the text you want to encode.
   - Save the image with the hidden text.

2. **Decoding Hidden Text from an Image**:
   - Select an image that contains hidden text.
   - The application will display the hidden message extracted from the image.

