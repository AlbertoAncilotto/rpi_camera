# Raspberry Pi Camera Python Code

This repository contains Python code for using the Raspberry Pi camera module.

## Enabling Camera for Raspberry Pi V1.3 Hardware

If you are using the Raspberry Pi V1.3 camera hardware, you need to enable the camera by adding a line to the `config.txt` file on the microSD card. Follow these steps:

1. Remove the microSD card from your Raspberry Pi.
2. Insert the microSD card into a card reader on your computer.
3. Navigate to the root directory of the microSD card.
4. Open the `config.txt` file in a text editor.
5. Add the following line to the end of the file:
    ```
    dtoverlay=ov5647
    ```
6. Save the file and eject the microSD card.