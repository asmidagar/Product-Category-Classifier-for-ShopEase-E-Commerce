# 🛍️ Product Category Classifier for ShopEase E-Commerce

An end-to-end deep learning project to automate product categorization using product descriptions and attributes. Built for **ShopEase E-Commerce**, this system classifies products like clothing, electronics, accessories, and more using **Artificial Neural Networks (ANN)** and **LSTM** models.

---

## 📌 Objective

The goal of this project is to build a robust multiclass classification system that accurately categorizes products based on their:
- **Textual descriptions**
- **Structured attributes** such as brand, color, material, size, and price

This automation helps reduce manual effort and improves the efficiency of inventory organization on e-commerce platforms.

---

## 🧠 Models Used

1. **Artificial Neural Network (ANN)**
2. **Long Short-Term Memory (LSTM)**

Both models were trained and evaluated, and the **ANN** model outperformed LSTM in terms of accuracy.

---

## 📂 Dataset

- Source: Provided internally for project use.
- Features include:
  - `description`
  - `brand`
  - `color`
  - `material`
  - `size`
  - `price`
  - `target_category` (label)

---

## 🛠️ Technologies & Libraries

- Python 3
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn
- TensorFlow / Keras
- NLP: Tokenizer, Embedding, LSTM
- Model Evaluation: Accuracy, Confusion Matrix, Classification Report

---

## 📈 Workflow

1. **Data Preprocessing**  
   - Filled missing values
   - Combined relevant text fields
   - Encoded target labels and structured features
   - Scaled numerical inputs

2. **EDA & Visualization**  
   - Category distribution
   - Brand frequency
   - Word cloud for descriptions

3. **Model Building**  
   - ANN: Text + structured inputs using dense layers
   - LSTM: Sequence model with embedding and memory

4. **Model Evaluation**  
   - Accuracy comparison
   - Confusion matrix
   - Classification report
   - Predicted class distribution

5. **Conclusion**  
   - ANN showed the best performance and is recommended for deployment.

---

## 🔍 Results

| Model | Accuracy |
|-------|----------|
| ANN   | **⬆️ Highest** |
| LSTM  | Moderate |

✅ ANN was selected as the final model due to its superior performance and stability.

---

## 📊 Sample Visualizations

- 📦 Confusion Matrix
- 📄 Classification Report
- 🔢 Predicted Category Distribution

---

## 📌 Project Summary

This project demonstrates how to combine **NLP + structured data** to solve real-world e-commerce problems.  
It offers a modular, extendable baseline for product categorization using deep learning.

---

## 👩‍💻 Author

**Asmi Dagar**  
Developed during internship/training with guidance and support.  
Feel free to explore and contribute!

---

## 🏷️ License

This project is for academic and learning purposes only.  
Please contact the author before reusing for commercial applications.

---

## 🙏 Acknowledgements

Special thanks to **YBI Foundation** for project support and mentorship.
