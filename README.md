# 🔥 Forest Fire Detection using Deep Learning

Forest fires are a major environmental concern, causing irreparable damage to ecosystems, wildlife, and human life. **Early detection** is critical in minimizing the impact and controlling the spread.  
This project leverages **deep learning** and **image classification** techniques to automatically detect signs of forest fires from visual data.

---

## 🎯 Project Objective

The goal of this project is to develop a Convolutional Neural Network (CNN)-based classifier that can accurately distinguish between:

- 🔥 **Fire** — Images showing visible forest fires
- 🌲 **No Fire** — Images without any fire present

---

## 🗃️ Dataset

- **Source:** [The Wildfire Dataset](https://www.kaggle.com/datasets/elmadafri/the-wildfire-dataset) (Kaggle)
- **Classes:**
  - 🔥 Fire
  - 🌲 NoFire

> **Note:** Dataset is not included in this repo due to size restrictions.  
> Update the paths `train_dir`, `val_dir`, and `test_dir` in the notebook as per your local setup.

---

## 🧠 Methodology

1. Load & structure the dataset using KaggleHub or manual extraction
2. Preprocess and augment the image data
3. Build a custom CNN model using TensorFlow/Keras
4. Train and validate the model over multiple epochs
5. Evaluate using classification metrics and test predictions

---

## 🛠️ Technologies Used

- 🐍 Python
- 🧠 TensorFlow / Keras
- 📊 Matplotlib, Seaborn
- 📦 NumPy, Pandas
- 📁 KaggleHub (for dataset access)

---

## 📈 Model Performance

- ✅ Final Validation Accuracy: **~72%**
- 🧠 Model Architecture:  
  `Conv2D → MaxPooling → Dropout → Flatten → Dense`

---

## 🧪 Sample Predictions

<table>
  <tr>
    <td><b>🔥 Fire Detected</b></td>
    <td><b>✅ No Fire Detected</b></td>
  </tr>
  <tr>
    <td><img src="plots/fire.png" width="250"/></td>
    <td><img src="plots/nofire.png" width="250"/></td>
  </tr>
</table>

---

## 📊 Training Performance

![Training Accuracy and Loss](plots/training_performance.png)

---

## 📊 Evaluation Metrics

### Confusion Matrix

![Confusion Matrix](plots/confusion_matrix.png)

### classification_report

![classification report](plots/classification_report.png)

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/Sakshi-0613/Forest_Fire_Detection_using_DL.git
cd Forest_Fire_Detection_using_DL

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook Forest_Fire_using_DL.ipynb
```
