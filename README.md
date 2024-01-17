# HMC-Grad: Automated Handwritten Multiple-Choice Test Grading

## Overview

HMC-Grad is a tool designed to automate the grading process of handwritten multiple-choice tests. It uses a Convolutional Neural Network (CNN) trained in PyTorch on the EMNIST dataset and OpenCV for image processing. The tool comes with a Gradio interface for easy interaction. 

## Features

- **No Specialized Hardware:** HMC-Grad eliminates the requirement for specialized hardware like OMR scanners, allowing accessibility through common devices such as smartphones equipped with a camera.

- **Simplified Answer Sheet Requirements:** Removing the need for custom printed answer sheets, HMC-Grad processes answers on standard yellow notepads.

- **Automated Grading:** Input a correction key (as a string of text) and the images (JPG) of the answer sheets, and HMC-Grad will provide the correctness and score for each one.

- **Item and Score Analysis:** Obtain detailed item-wise analysis along with an overall score analysis.

- **Export Results:** HMC-Grad generates CSV and XLSX files containing the results, making it easy to integrate with other tools or platforms.

## Prerequisites

- Google Colab environment

## Usage on Google Colab

1. Open the provided notebook (`hmc_grad.ipynb`) in Google Colaboratory.

2. Execute all the cells in the notebook to run HMC-Grad in a user-friendly Gradio interface.

3. Scroll down and open the generated Gradio public URL.

4. Upload your correction key and the images of the answer sheets into the respective input fields. The system can handle any number of image inputs.

5. Download the results you need.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or issues, please contact gabriel.edradan05@gmail.com.
