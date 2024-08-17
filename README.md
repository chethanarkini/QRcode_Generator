# QR Code Generator

This Python project is a user-friendly QR Code Generator with a graphical interface built using the Tkinter library. It allows users to create and save QR codes of customizable sizes for any website, application, or text.

## Features

- **Generate QR Codes:** Easily create QR codes by entering any text or URL.
- **Custom Size:** Specify the size of the QR code, ranging from 1 to 40 (with 1 being the smallest and 40 being the largest).
- **Save as Image:** Save the generated QR code as a PNG image file in a location of your choice.
- **User Interface:** A simple, intuitive interface designed using Tkinter.

## Requirements

- Python 3.x
- Required libraries:
  - `qrcode`
  - `Pillow` (included with the `qrcode` package)
  - `tkinter` (usually included with Python)

## Generate a QR Code:
- Enter the text or URL you wish to encode in the first input field.
- Specify the location where you want to save the QR code image in the second input field.
- Enter a name for the image file in the third input field (do not include the file extension).
- Choose a size for the QR code (1 to 40) in the fourth input field.
- Click the "Generate Code" button to create and save your QR code.
## Saving the QR Code:
- After generating the QR code, a pop-up message will confirm that the QR code has been successfully saved.
