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


            Artificial Intelligence-Based Malaria Risk Predictor
Overview

Malaria remains one of the most deadly and common diseases in the majority of developing countries, particularly sub-Saharan Africa. Incidence has continued to increase despite widespread public health interventions founded on late response, climate change, and limited predictive resources.

This project offers a simple yet powerful machine learning method designed to predict malaria risk zones based on environmental and socio-economic data. The intention is to provide health authorities with fact-based evidence that prevents the incidence of outbreaks from happening in the first place.

    Problem Statement
Malaria control traditionally relies on history and reactive responses. But before cases are reported, the outbreaks may already be spreading. Most regions lack real-time analytics to predict malaria hotspots because of changing conditions like temperature, rainfall, and availability of preventive gear.

Without forecasting analysis, countries suffer from:

Ineffective distribution of resources (e.g., insecticide-treated bed nets, medicines)

Slow emergency response
Indirectly mounting infections and preventable deaths

     AI/ML Solution
I built a machine learning classification model that predicts whether a region is at high or low risk for malaria based on the following features:

Temperature (°C)

Humidity (%)

Rainfall (mm)

Population Density (people/km²)

Mosquito Net Usage (% of population)

All these variables have direct association with the propagation of malaria. By feeding this data into a Random Forest Classifier, the model can ascertain risk-prone regions prior to cases surfacing.

    How It Works
Data Collection: The dataset was reduced to use environmental and demographic characteristics and malaria risk labels.

Model Training: The data was split into training and test sets through scikit-learn.

Prediction & Evaluation: A model was trained using Random Forest to predict malaria risk with a good level of accuracy.

Output: The model will predict if an area is high-risk (1) or low-risk (0).

✅ SDG Alignment
This project aligns with:

SDG 3: Good Health and Well-Being
Target: End epidemics of malaria and other infectious diseases.

It also indirectly contributes to:

SDG 1: No Poverty, through the protection of vulnerable communities

SDG 13: Climate Action, through the demonstration of the effects of climate on health

     Results & Insights
In validation, the model accurately predicted high-risk areas from sparse data points. With better real-world data sets (e.g., from ministry of health or WHO), the model can be more accurate and scaled up to real-time dashboards or SMS alert to rural health workers.

      Future Potential
Utilize satellite and geospatial data for improved accuracy

Deploy the model in mobile/web apps for health officers

Use it in conjunction with government statistics to maximize malaria intervention programs

👩🏽‍💻 Author
Channelle W Kibunyi
Student – Power Learn Project: AI for Sustainable Development
Project: AI-Powered Malaria Risk Predictor
GitHub: [https://github.com/channelle005]


