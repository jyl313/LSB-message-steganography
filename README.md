# LSB-message-steganography
Simple implementation of Least Significant Bit(LSB) message steganography

### Requirements*
- Python 3
- Pillow
- Numpy
> ***Set up anaconda environment with the provided `environment.yml`**

### Code execution
1) Run `python LSB_msg.py` in command prompt
2) A prompt will ask user to enter:
> - **1** for message encoding(go to **3** next)
> - **2** for message decoding(go to **4** next)
3) For message encoding(1), user will be prompted to enter:
> - Full path to image to be encoded(with extension)
> - Message to be encoded
> - Encoded image filename to be saved(without extension)
4) For message decoding(2), user will be prompted to enter:
> - Full path to image to be decoded(with extension)
