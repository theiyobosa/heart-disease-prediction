<h1>Heart Disease Prediction</h1>

<h2>Dataset</h2>

The dataset contains info on patients with and without heart diseases.

The attributes include:

- age: Age in years
- sex: 1 = male, 0 = female
- cp: Chest pain type
- trestbps: Resting blood pressure (in mm Hg on admission to the hospital)
- chol: serum cholesterol in mg/dl
- fbs: fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- restecg: Resting electrocardiographic results
- thalach: Maximum heart rate achieved
- exang: Exercise induced angina (1 = yes; 0 = no)
- oldpeak: ST depression induced by exercise relative to rest
- slope: The slope of the peak exercise ST segment
- ca: Number of major vessels (0-3) colored by fluoroscopy
- thal: 3 = normal; 6 = fixed defect; 7 = reversible defect
- target: 1 = Heart disease present, 0 = Heart disease not present

<h2>Objective</h2>

The objective is to use the first thirteen features to predict whether or not a patient has heart disease.

<h2>Libraries used</h2>

The libraries used within this repository are:

- NumPy
- Pandas
- scikit-learn
- matplotlib
- seaborn

<h2>Approach</h2>

EDA was performed on the dataset. The dataset was also split, 80% of it was used for training, and the other 20% was used for testing. The model was tranined on a Random Forest Classifier model.

<h2>Results</h2>

The model used had an accuracy of almost 100% on the traning set, and an accuracy of 86.8% on the test set.
