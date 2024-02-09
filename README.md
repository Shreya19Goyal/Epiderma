# Epiderma: Skin Cancer Classification with CNN

## Introduction

Epiderma is a deep learning project aimed at classifying skin cancer images into different categories using Convolutional Neural Networks (CNNs). The dataset used for training is HAM10000, which comprises images of various types of skin lesions. This project is beneficial for dermatologists and medical practitioners in accurately diagnosing skin cancer at an early stage.

## Dataset

The HAM10000 dataset consists of 10015 dermatoscopic images, categorized into 7 classes:

1. Actinic keratoses and intraepithelial carcinomae (akiec)
2. Basal cell carcinoma (bcc)
3. Benign keratosis-like lesions (bkl)
4. Dermatofibroma (df)
5. Melanoma (mel)
6. Melanocytic nevi (nv)
7. Vascular lesions (vasc)

Each image is accompanied by metadata, including lesion type and patient information.

## Model Architecture

Epiderma employs a CNN architecture for image classification. The model is trained on a subset of the HAM10000 dataset, optimizing for accuracy and generalization. Key components of the model include:

- Convolutional layers for feature extraction
- Pooling layers for dimensionality reduction
- Fully connected layers for classification
- Dropout layers for regularization

The model is trained using TensorFlow and Keras libraries, enabling efficient computation and seamless integration with other deep learning tools.

## Usage

To use Epiderma for skin cancer classification:

1. Clone the repository: `git clone https://github.com/Shreya19Goyal/Epiderma.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Download the pre-trained model: [Model Link]([https://your_model_link.h5](https://github.com/Shreya19Goyal/Epiderma/blob/main/model.h5))
4. Run the prediction script: `python predict.py --image_path <path_to_image>`


## Results

Epiderma achieves promising results in skin cancer classification, with accuracy exceeding XX%. The model's performance is validated on a separate test set, demonstrating its efficacy in real-world scenarios.

## Acknowledgments

- Kaggle for providing the HAM10000 dataset
- Open-source contributors for libraries and tools used in the project

## Contact

For inquiries or suggestions, feel free to contact the project maintainer at goyalshreya1908@gmail.com. Contributions and feedback are always welcome!

---

Feel free to customize this README according to your project specifics. Good luck with your project, and happy coding!
