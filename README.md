# Chest CT Scan Cancer Detection Model

## Overview
This project is focused on detecting lung cancer using deep learning techniques on **Chest CT Scan images**. The dataset consists of CT scan images categorized into four classes:

- **Adenocarcinoma**
- **Large Cell Carcinoma**
- **Normal**
- **Squamous Cell Carcinoma**

The images are preprocessed and used to train a deep learning model to classify lung cancer types effectively.

## Dataset
The dataset is structured as follows:
```
![image](https://github.com/user-attachments/assets/88657cd7-55fa-446a-91a8-ddba6fa4f811)


## Dependencies
Make sure you have the following libraries installed before running the project:
```bash
pip install numpy pillow scikit-learn keras tensorflow
```

## Installation & Usage
1. Clone the repository:
```bash
git clone https://github.com/your-username/chest-ct-scan-detection.git
cd chest-ct-scan-detection
```

2. Run the dataset loading script:
```bash
python load_dataset.py
```
This script:
- Loads and preprocesses the images
- Splits the dataset into training and validation sets
- Encodes the labels for model training

3. Train the deep learning model (To be implemented)
```bash
python train_model.py
```

4. Evaluate the model (To be implemented)
```bash
python evaluate_model.py
```

## Model Architecture
The project aims to utilize **ResNet50** as the base model, fine-tuned for classification.

## Results
Once the model is trained, performance metrics such as accuracy, precision, recall, and confusion matrices will be generated.

## Contribution
Feel free to contribute to this project by:
- Adding new model architectures
- Improving dataset preprocessing
- Enhancing visualization for results

## License
This project is open-source and available under the MIT License.

## Contact
For questions or suggestions, feel free to reach out via GitHub Issues or email:aditighosh138@gmail.com.

---
*Happy coding! 🚀*

