# Generative AI Models (2AMU20) Assignment 3

This repository contains the third assignment for the Generative AI Models course (2AMU20) at Eindhoven University of Technology. The assignment focuses on converting low-resolution grayscale images into high-resolution colored images by combining two advanced generative models: conditional Generative Adversarial Networks (cGAN) for colorization and Super-Resolution GAN (SRGAN) for enhancing image resolution.

### Key Components
1. **Image Colorization**: Utilizing cGAN to colorize grayscale images.
2. **Super-Resolution**: Utilizing SRGAN to enhance the resolution of images.
3. **Integration**: Combining both models to transform 64x64 grayscale images into 256x256 high-resolution colored images.

### Training Data
- **Colorization Model**: Trained on a subset of the COCO dataset comprising 10,000 images.
- **Super-Resolution Model**: Trained on the PASCAL dataset using 10,000 images.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/luca-mainardi/Image-Colorization-and-SuperResolution.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Image-Colorization-and-SuperResolution/
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Follow the instructions in the provided Jupyter notebooks to set up the environment and run the code. \
You can download the weights of the models at this link: https://drive.google.com/drive/folders/1dOVFTqZ9uaPBzkVa-gVxZgGIEZy9m125?usp=sharing. \
It is recommended to run the project on Google Colab or kaggle.


## Contributors
- **Luca Mainardi**
- **Francesco Brescia**
- **Matthew Nana**


