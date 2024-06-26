
# PHOTO MOSAIC

This project implements a photo mosaic generator using Python. It allows users to convert an image into a mosaic composed of smaller tile images. The project aims to create a visually appealing and artistic representation of the original image with high efficiency.
The motivation behind this project stemmed from exploring image processing techniques and creating a fun and creative application of Python. It addresses the challenge of transforming an image into a unique mosaic artwork.


## Features

- **Parallelization:** Used **"multiprocess"** library to utilize each core of the CPU to fit tile images to generate the final mosaic. 
- **Image Resizing:** Used **"pillow"** library to resize our tile images to the same size as the main image tiles, improving efficiency.
- **GUI:** Used **"tkinter"** library to provide a basic yet user-friendly UI for the user to complete the operation.


## Installation

Install photo-mosaic with pip

```bash
    pip install pillow multiprocess
```
    
## Sample Output

![alt text](https://github.com/jayantknaik/PhotoMosaic/blob/master/mosaic.jpeg?raw=true)

## Sample Input

![alt text](https://github.com/jayantknaik/PhotoMosaic/blob/master/Media/source.jpg?raw=true)