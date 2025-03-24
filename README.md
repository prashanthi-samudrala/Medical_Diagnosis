Disease Prediction Web Application
Overview
This web application project is designed with Streamlit to predict different diseases from user input. It employs machine learning models for making predictions for the diseases listed below:
- Diabetes
- Heart Disease
- Parkinson's Disease
- Lung Cancer
- Hypo-Thyroid

Features
- Easy-to-Use Interface: Developed in Streamlit so that it is convenient to use.
- Machine Learning Models: Employs trained models for predicting the diseases.
- Secure and Fast: Inputs are processed and results are delivered efficiently.
- Interactive UI: Displays an interactive entry form to input required medical parameters.

Installation
To execute this project on the local machine, do the following:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/disease-prediction.git
   ```
2. Go to the project directory:
   ```bash
   cd disease-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Execute the Streamlit application:
   ```bash
streamlit run app.py
```


Dependencies
The following Python libraries are required by the application:
- Streamlit
- Pickle
- scikit-learn
- pandas
- numpy

Usage
1. Launch the web application.
2. Choose the disease you wish to predict from the drop-down menu.
3. Enter the necessary parameters.
4. Click on the prediction button to view the output.

File Structure
```.
├── app.py                     Main application file
├── Models/                    Directory for trained ML models
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   ├── parkinsons_model.sav
│   ├── lungs_disease_model.sav
│   ├── Thyroid_model.sav
├── notebooks/                Jupyter Notebooks for training models
│   ├── Heart_Disease_Prediction.ipynb
│   ├── Lung_Cancer.ipynb
│   ├── Parkinson's_Disease_Detection.ipynb
│   ├── Thyroid.ipynb
├── requirements.txt           Python libraries required
├── README.md                  Project documentation
```

Contributing
Contributions are always welcome! Please feel free to fork this repository and send a pull request.

License
This project is licensed under the MIT License.

Acknowledgments
We would like to extend special thanks to the open-source community and medical researchers for providing healthcare-related AI solution datasets and tools.

