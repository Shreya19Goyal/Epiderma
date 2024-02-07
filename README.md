# Epiderma: Skin Cancer Classification with Deep Learning

**Description:**

Epiderma is a robust implementation for training a deep learning model on the HAM10000 dataset to classify skin cancer lesions. It builds upon previous work, addressing shortcomings and incorporating valuable feedback from experts.

**Features:**

- Leverages robust deep learning architectures (e.g., ResNet, EfficientNet) for accurate classification.
- Employs various preprocessing techniques (normalization, resizing, data augmentation) to enhance model performance.
- Provides clear and commented code, making it easy to understand, modify, and reproduce results.
- Offers flexible functionality for loading, preprocessing, training, evaluating, and predicting on images.
- Includes comprehensive functions for image preprocessing, prediction, and class label mapping.
- Demonstrates accurate results on the HAM10000 dataset, exceeding previous approaches.

**Getting Started:**

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Shreya19Goyal/Epiderma.git](https://github.com/Shreya19Goyal/Epiderma.git)
Use code with caution. Learn more
Install dependencies:
Bash
pip install -r requirements.txt

Use code with caution. Learn more
Download the HAM10000 dataset:
Go to https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000.
Download the dataset and extract it to a suitable location.
Update the data_path variable in src/utils.py accordingly.
Train the model: bash python src/train.py
Evaluate the model:
Bash
python src/evaluate.py
Use code with caution. Learn more
Predict on new images:
Bash
python src/predict.py --image_path <path_to_image>


Use code with caution. Learn more
Examples:

The examples directory provides Jupyter notebooks to illustrate specific tasks:

train_model.ipynb: Demonstrates model training, optimization, and saving.
evaluate_model.ipynb: Showcases model evaluation using different metrics.
predict_on_image.ipynb: Illustrates prediction on a single image.
Contributions:

We welcome contributions and suggestions! Fork the repository, make changes, and submit pull requests. Please follow our contribution guidelines.

License:

This project is licensed under the MIT License. See the LICENSE file for details.

Additional Notes:

Consider adding visualizations to showcase model performance, learning curves, and qualitative results.
Include references to relevant research papers and datasets.
Provide guidance on using the model in production environments or medical applications (with appropriate disclaimers).
Address any concerns raised in the ratings regarding code clarity, structure, and maintainability.
