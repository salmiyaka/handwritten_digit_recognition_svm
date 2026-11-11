
#  HANDWRITTEN DIGIT RECOGNITION USING SVM

### Machine Learning Project | Python | Support Vector Machine

---

## 📌 Project Overview

This project demonstrates how Machine Learning can recognize handwritten digits using a Support Vector Machine (SVM) classifier.

The model takes an image of a handwritten digit and predicts which number it represents, from 0 to 9.

The project uses 8×8 pixel images, where each image is represented by 64 numerical pixel values.

## 🎯 Project Objectives

- Understand how images are represented as numerical data.
- Load and explore the handwritten digit dataset.
- Visualize handwritten digit images.
- Train a Support Vector Machine (SVM) model.
- Predict handwritten digits from image data.
- Compare different SVM configurations.

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 🤖 Machine Learning Algorithm

**Support Vector Machine (SVM)**

The project uses SVM for multi-class classification to recognize digits from 0 to 9.

Different configurations are compared using:
- Linear Kernel
- RBF Kernel
- Gamma parameter
- C parameter

## 📊 Dataset Information

The project uses `digits.csv`, containing:

- 1,797 handwritten digit images.
- 64 pixel values per image.
- One label representing the actual digit (0–9).

Each image is represented as an 8×8 pixel grid.

## 📂 Project Structure

```text
handwritten_digit_recognition_svm/
│
├── 02_handwritten_digit_recognition_svm.ipynb
├── README.md
└── data/
    └── digits.csv
```

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/handwritten_digit_recognition_svm.git
```

2. Install the required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

3. Place `digits.csv` inside the `data` folder.

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Run the notebook:

`02_handwritten_digit_recognition_svm.ipynb`

## 📈 Expected Output

- Visualization of handwritten digits.
- Training and testing of the SVM model.
- Digit prediction results.
- Accuracy comparison between different SVM configurations.

## 👨‍🏫 Credits

Original project provided by our instructor for educational purposes and learning.

## 📚 Learning Outcome

This project demonstrates the basics of image representation, supervised machine learning, classification, prediction, and model evaluation.

---
