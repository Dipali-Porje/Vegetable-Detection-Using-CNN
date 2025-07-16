# 🥦 Vegetable Detection System using CNN with Tkinter GUI

This project is a desktop-based application that uses a **Convolutional Neural Network (CNN)** to detect and classify vegetables from images. The application features a simple and interactive **Tkinter GUI**, making it easy to use for non-technical users as well.

---

## 🥕 Vegetables Detected

The model is trained to recognize multiple vegetables, such as:
- 🥔 Potato
- 🥒 Cucumber
- 🍅 Tomato
- 🧅 Onion
- 🥦 Broccoli
- 🥕 Carrot
- 🫑 Capsicum  
- Lemon

---

## 🧠 Model Info

- **Model Type**: CNN (Convolutional Neural Network)
- **Input Image Size**: e.g., 150x150 or 224x224
- **Framework**: TensorFlow / Keras
- **Output**: Vegetable class label with prediction confidence

---

## 🖥 GUI Features (Tkinter)

- 📂 Upload image of a vegetable
- 🤖 Perform prediction using a trained CNN model
- 📝 Display prediction label and confidence
- 🔄 Reset or upload a new image
- 🪄 Easy-to-use interface suitable for all users

---

## 🗂 Project Structure

vegetable_detection_gui/
├── vegetable_model.h5 # Trained CNN model
├── vegetable_prediction_model.ipynb
├── prediction
├── requirements.txt
└── README.md


---

## 🚀 How to Run the Application

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Dipali-Porje/Vegetable-Detection-Using-CNN.git
cd Vegetable-Detection-Using-CNN

### 2️⃣ Install Required Libraries
pip install -r requirements.txt

### ✨ Future Improvements

Add webcam integration for real-time vegetable detection
Enhance UI with better layout and visuals (e.g., ttkbootstrap)
Add voice feedback for accessibility
Show top 3 predictions with bar graph



