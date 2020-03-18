# LSBR-message-steganography
Simple implementation of Least Significant Bit Replacement(LSBR) message steganography

### Requirements
- Windows 10 x64
- Python 3
- Pillow
- Numpy
> ***Set up anaconda environment with the provided `environment.yml`**

### Code execution
The following will run through the code execution in steps of inputs to enter and expected output

1) Execute `python lsbr_msg.py` in command prompt
2) A prompt will ask user to enter:
> - **1** for message encoding
> - **2** for message decoding
3) For message encoding(1), user will be prompted to enter the following in order*:
> *After entering each prompt, press enter to submit
> - Full path to image to be encoded(with extension)
> - Message to be encoded
> - Encoded image filename to be saved(without extension)
4) Embedded/stego image will be saved as a *png* image with the indicated filename
5) For message decoding(2), user will be prompted to enter:
> - Full path to image to be decoded(with extension)
6) The embedded message(if any) will be shown as output

### Sample images
Sample images(taken from Windows10 wallpapers) are provided for use
