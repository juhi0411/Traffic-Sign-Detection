# 🚦 Road Traffic Sign Recognition

## 📖 Overview
Traffic Sign Recognition is the process of automatically identifying which class a given traffic sign belongs to.  
Earlier, traditional Computer Vision methods required heavy manual feature extraction. Today, **Deep Learning (CNNs)** make this task more accurate and efficient.  

The goal of this project is to build a traffic sign recognition system for **autonomous vehicles** using the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset.

![trafficSR](https://user-images.githubusercontent.com/55687431/86936099-2da20900-c15b-11ea-991a-508e9b86ecc1.jpg)
---

## 📊 Dataset
- **Dataset**: [German Traffic Sign Recognition Benchmark (GTSRB)](https://benchmark.ini.rub.de/gtsrb_news.html)  
- **Classes**: 43 different traffic sign categories  
- **Training set**: 39,209 labeled images  
- **Test set**: 12,630 images  

---

## 🛠️ Environment Used
- Anaconda (Jupyter Notebook & Spyder)  
- PyCharm  
- VS Code  

---

## 📦 Libraries / Dependencies
- **Core**: `numpy`, `pandas`, `matplotlib`, `os`  
- **Machine Learning**: `scikit-learn`, `tensorflow`, `keras`  
- **Utilities**: `pillow`  
- **GUI**: `tkinter`  

---

## ⚙️ Steps to Build the Project
1. Setup the project & create a virtual environment.  
2. Install required dependencies.  
3. Load and preprocess dataset (resize, normalize images).  
4. Split dataset using `train_test_split`.  
5. Convert labels into one-hot vectors using `to_categorical()`.  
6. Build CNN model with Keras (Conv2D, MaxPooling2D, Dropout, Flatten, Dense).  
7. Compile with:
   - Optimizer: **Adam**  
   - Loss: **categorical_crossentropy**  
   - Metric: **accuracy**  
8. Train the model using `model.fit()`.  
9. Evaluate on validation/test dataset.  
10. Save trained model as `model_RTSR.h5`.  
11. Deploy using:
    - `interface.py` (Tkinter GUI), or  
    - Flask web app (optional).  

---

## 📈 Model Evaluation
- **Validation Accuracy**: ~97.09%  
- **Test Accuracy**: ~96.37%  

---

## 📂 Repository Contents
1. **Datasets/** → Kaggle dataset link (via script)  
2. **Demo Images/** → Screenshots of output  
3. **Project Info/** → Project PPT  
4. **Road Traffic Sign Recognition.ipynb** → Jupyter Notebook (model + predictions)  
5. **interface.py** → Tkinter GUI for deployment  
6. **train_model.py** → Model training script  
7. **load_data.py** → Dataset loading & preprocessing  
8. **download_dataset.py** → Kaggle dataset download script  
9. **manual_setup.py** → Manual setup helper  
10. **model_RTSR.h5** → Saved trained model  
11. **Project Demonstration.zip** → Demo video of results  

---

## 🚀 Usage

### 1. Clone Repository
```bash
git clone https://github.com/sunilprajapat1408/Road-Traffic-Sign-Recognition.git
cd Road-Traffic-Sign-Recognition

👨‍💻 Author

Sunil Prajapat
📍 India
📧 Email: sunilprajapat2907@gmail.com
🔗 GitHub: sunilprajapat1408

🔗 LinkedIn: linkedin.com/in/sunil-prajapat-878663282

