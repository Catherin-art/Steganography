# Cybersecurity - Steganography
Secure Data Hiding in Image Using Steganography
    This project implements a simple steganography technique to securely hide a secret message inside an image using OpenCV in Python.

Features:
*Encrypts a secret message into an image.
*Uses a passcode for decryption.
*Extracts and displays the hidden message upon correct passcode entry.
*Uses pixel modification for data encoding.
*Prerequisites

Ensure you have the following installed:
Python 3.x
OpenCV (cv2)
OS module (built-in)



Installation:
1.Clone this repository
git clone https://github.com/catherin-art/steganography.git
cd steganography

2.Install dependencies
pip install opencv-python


Usage

1.Place your input image in the project directory.

2.Update the script with the correct image path.

3.Run the script:
python steganography.py

4.Enter a secret message and passcode.

5.The encoded image will be saved and opened automatically.

6.Run the script again, enter the correct passcode, and retrieve the hidden message.

Code 

Notes:

1.Ensure the image has enough pixels to store the message.

2.The encryption modifies pixel values; excessive modifications may alter the image visibly.

3.Make sure to provide the correct image path in the script to avoid file loading errors.




