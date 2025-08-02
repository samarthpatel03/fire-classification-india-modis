# fire-classification-india-modis

This project analyzes and classifies fire incidents in India using MODIS satellite data from 2021, 2022, and 2023. The objective is to classify different fire types and explore their geographical and confidence-level distributions using machine learning and data visualization.

## 🔍 Features

- Loads and merges MODIS fire data for three years (2021–2023)
- Performs detailed exploratory data analysis (EDA)
- Visualizes fire type and confidence level distributions
- Trains and evaluates multiple machine learning models
- Final model (Random Forest) deployed via Streamlit web app
- Includes confusion matrix and model accuracy evaluation


## Project Structure

```
Edunet/
├── Data/
│ ├── modis_2021_India.csv
│ ├── modis_2022_India.csv
│ └── modis_2023_India.csv
├── fire-classification-india-modis.ipynb
├── app.py
├── best_fire_detection_model.pkl
├── scaler.pkl
├── requirements.txt
└── README.md
```


## ⚙️ Requirements

- Python 3.11.0
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- streamlit
- joblib

Install dependencies with:

```
pip install -r requirements.txt
```


## 🚀 Usage

1. Place the MODIS CSV files in the `Data/` directory.
2. Open `fire-classification-india-modis.ipynb` in Jupyter Notebook or VS Code.
3. Run the notebook to load data, analyze trends, and train the classifier.
4. To run the deployed model as a web app:

streamlit run app.py

## Link to the model:
https://drive.google.com/file/d/1RDLc1K4WxAzRGl515a-389TUPSPRSL5-/view?usp=drive_link
## 📊 Visualizations

- **Fire Type Distribution:** Bar plot showing the count of each fire type.
- **Confidence Distribution:** Histogram showing frequency of confidence levels (low, nominal, high).
- **Model Evaluation:** Includes accuracy score and confusion matrix plots for all trained models.

## 📝 Notes

- Ensure the CSV data files are correctly named and placed in the `Data/` folder.
- If you change file locations, update the file paths in the notebook accordingly.
- The final model and scaler are saved as `.pkl` files and used in the Streamlit deployment.

---

Let me know if you want a badge section (e.g. license, Python version, etc.) or link to datasets or app demo!
