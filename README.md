# classifying-plants-based-on-water-needs
classifying plants based on water needs
# 🌱 Plant Classification Based on Water Needs

This project predicts the water requirements of plants based on environmental conditions and physical characteristics such as sunlight exposure, watering frequency, and soil type. It uses a Random Forest Classifier trained on a sample dataset.

---

## 📁 Dataset

The dataset (`plants.csv`) includes the following columns:

- `sunlight_hours`: Average daily sunlight in hours  
- `watering_freq_per_week`: How many times the plant is watered per week  
- `soil_type`: Type of soil (e.g., Sandy, Loamy, Clay)  
- `water_need`: Target label (Low, Moderate, High)

---

## 🧠 Technologies Used

- Python  
- Pandas  
- Seaborn & Matplotlib (for visualization)  
- Scikit-learn (for machine learning and evaluation)

---

## ⚙️ How It Works

1. **Load the dataset**
2. **Encode categorical variables** (`soil_type` and `water_need`)
3. **Split into training and testing sets**
4. **Train a Random Forest Classifier**
5. **Evaluate the model** using:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
6. **Visualize** results using a confusion matrix
