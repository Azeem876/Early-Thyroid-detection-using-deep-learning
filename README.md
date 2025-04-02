**Early Thyroid Detection using Hybrid CNN-GAT Model**

**Project Overview**

This project focuses on early detection of thyroid abnormalities using a hybrid model combining Convolutional Neural Networks (CNN) and Graph Attention Networks (GAT). The aim is to improve detection accuracy by leveraging both spatial and relational information from ultrasound images. The model is particularly designed for the detection of thyroid conditions using ultrasound data from a Kaggle dataset.

**Model Architecture**

The proposed model utilizes the EfficientNet-B4 architecture integrated with GAT layers. The EfficientNet-B4 model is used to extract spatial features, while GAT layers capture relational dependencies between image patches. The combination of these two techniques allows the model to effectively capture both local and global patterns in thyroid ultrasound images.

**Dataset**

The model is trained on a publicly available thyroid ultrasound image dataset from Kaggle. The dataset contains labeled ultrasound images indicating different thyroid conditions.

**Installation**

**Clone the repository:**

git clone https://github.com/username/thyroid-detection

Navigate to the project directory:

cd thyroid-detection

Install the required packages:

pip install -r requirements.txt

**Usage**

**Preprocess the dataset:**

python preprocess.py

**Train the model:**

python train.py --config config.yaml
**
Evaluate the model:**

python evaluate.py --model best_model.pth

**Results**

The model achieved significant accuracy improvements compared to conventional CNN-based methods. Performance metrics such as accuracy, precision, recall, and F1-score are presented in the results folder.

**Future Work**

Optimization of GAT layers to reduce computational cost.

Incorporation of more diverse datasets to improve generalization.

Exploration of other graph-based architectures.

**Contributing**

Feel free to open issues or submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

**License**

This project is licensed under the MIT License - see the LICENSE file for details.

