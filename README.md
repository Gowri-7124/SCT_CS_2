Image Encryption Tool

This is a simple GUI-based Python application that allows users to encrypt and decrypt images using a seeded pseudo-random pixel shuffling technique.

Features

Select any image file and apply encryption using a seed-based pixel shuffle.

Decrypt the encrypted image back to its original form using the same seed.

Simple and intuitive interface built using tkinter.

How It Works

The tool scrambles image pixels based on a user-provided seed value, producing an encrypted image. To decrypt, the same seed is used to reverse the pixel shuffling, restoring the original image.

Dependencies

Python 3.x

Pillow (PIL)

tkinter (comes bundled with Python on most distributions)

Install Pillow via pip:

pip install Pillow

How to Run

Save the script as image_encryption_tool.py.

Run it using Python:

python image_encryption_tool.py

Use the GUI to:

Browse and select an input image.

Choose the output path to save the result.

Enter a numeric or text seed (used for encryption/decryption).

Click "Encrypt Image" or "Decrypt Image".

Encryption Logic

The pixel data of the image is retrieved.

A list of indices is shuffled using a pseudo-random generator seeded with the user’s input.

Pixels are rearranged based on the shuffled indices.

For decryption, the same seed is used to reconstruct the original order.

Notes

Ensure to use the same seed for decryption as was used for encryption.

Supports common image formats like PNG and JPEG.

Author

Gowri Javgal
