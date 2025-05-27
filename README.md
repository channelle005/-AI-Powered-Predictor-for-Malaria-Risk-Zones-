# -AI-Powered-Predictor-for-Malaria-Risk-Zones-

# 🌍 AI-Powered Malaria Risk Predictor

## 🔬 SDG Focus
**Sustainable Development Goal 3: Good Health and Well-Being**  
This project supports efforts to reduce the global burden of malaria by enabling proactive health intervention through AI.

---

## 🧠 About the Project
This machine learning solution predicts whether a given region is at **high** or **low risk** for malaria, based on environmental and social factors.  
It empowers healthcare organizations, NGOs, and local governments to allocate resources more efficiently and respond to malaria threats before outbreaks occur.

---

## 📊 Dataset
The model uses structured data including:
- Temperature (°C)
- Humidity (%)
- Rainfall (mm)
- Population Density (people/km²)
- Mosquito Net Usage (0–1 scale)
- Malaria Risk (0 = low, 1 = high)

You can modify or extend the dataset to include more features like elevation, previous case numbers, or sanitation index.

---

## 🔧 Technologies Used
- Python
- Pandas
- Scikit-learn
- Random Forest Classifier
- Google Colab / Jupyter Notebook

---

## 🚀 How to Run the Project

1. Clone the repository or upload the files to your Google Colab environment.
2. Ensure `malaria_data.csv` is in the same directory as your `.py` or notebook file.
3. Run the script `malaria_predictor.py`.
4. The model will:
   - Load and preprocess the dataset
   - Train a classification model
   - Predict malaria risk
   - Display accuracy and a performance report

---

## 📌 Results
The model aims to achieve high accuracy in classifying malaria risk, which can support early warning systems and policy decisions in affected regions.

---

## 📬 Author
**Channelle W Kibunyi**  
Student, Power Learn Project – AI for Sustainable Development Cohort  
Email: *(channellekibunyi3@gmail.com)*  
GitHub: *(https://github.com/channelle005)*

---

## 💡 Future Improvements
- Use geospatial data for risk mapping
- Incorporate satellite or remote sensing data
- Deploy as a mobile or web-based AI tool for public health officers
