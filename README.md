# 🧠 Handwritten Digit Classification Using CNN in Keras

## 📌 About the Project
This project demonstrates how to build a Convolutional Neural Network (CNN) using Keras for classifying handwritten digits. The input data is provided in **CSV format**, where each image is stored as a flattened array of pixel values along with its corresponding label (0–9).

## 🛠️ Technologies Used
- Python  
- TensorFlow & Keras  
- NumPy, Pandas  
- Matplotlib for visualization  

## 📁 Dataset
The dataset is hosted on Kaggle.

👉 [Click here to download the dataset](https://www.kaggle.com/datasets/bamboonotes/handwritten-digits)  

## 🧮 Model Architecture
- **Input Layer:** Reshaped 28x28 grayscale image  
- **Conv2D + ReLU Activation**  
- **MaxPooling2D**  
- *(Repeated Conv-Pool layers as needed)*  
- **Flatten**  
- **Dense Layers**  
- **Output Layer:** Softmax activation for 10-class classification  

## 📈 Results
The model classifies digits from 0 to 9 with high accuracy.

**Evaluation includes:**
- Classification accuracy
- Confusion matrix
- Visual prediction samples

**Example predictions:**
Input: [🖊️ handwritten "5"] → Predicted: 5
Input: [🖊️ handwritten "7"] → Predicted: 

**Final test accuracy:** ~98%
## 🚀 How to Run
1. Clone this repo  
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   jupyter notebook digit.ipynb


---

⭐ Feel free to fork, experiment, or contribute to enhance the model or deploy it using Streamlit or Flask!
