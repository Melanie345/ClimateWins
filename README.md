# ClimateWins
Learning to help predict the consequences of climate change around Europe through machine learning
# Introduction
ClimateWins is interested in using machine learning to help predict the consequences of climate change around Europe and, potentially, the world. We assessed the tools available to categorize and predict the weather in mainland Europe.  It's concerned with the increase in extreme weather events, especially in the past 10-20 years. With data from the past century, it hopes to create a model for what the future will hold.
# Key Questions
-  How is machine learning used? Is it applicable to weather data?
-  ClimateWins has heard of ethical concerns surrounding machine learning and AI. Are there any concerns specific to this project?
-  Historically, what have the maximums and minimums in temperature been?
-  Can machine learning be used to predict whether weather conditions will be favorable on a certain day? (If so, it could also be possible to predict danger.)

# Data Sets
Data set was based on weather observations from 18 different weather station across Europe, which contain data ranging from the late 1800s to 2022.  Recordings exist for almost everyday with values such as temperature, wind speed, snow, global radiation and more.  

-  dataset-weather-prediction-dataset-processed.csv
-  dataset-Answers-Weather_Prediction_Pleasant_Weather.csv
Data is collected from the European Climate Assessment & Data Set project.

# Libraries
The data analysis and visualizations were conducted using Jupyter notebooks in the Python Environment, the libraries used:
Core Libraries
-  Pandas: for data analysis
-  Numpy: for mathematical equations
-  Seaborn: for data visualizations
-  Matplotlib: for data visualizations
-  os: for handling file paths, creating and removing directories, retrieve environment variables, and run basic system commands
Machine Learning and Data Processing:
-  scikit-learn: For machine learning models, metrics, and data preprocessing tools.
    -  Modules include:
      -  accuracy_score, confusion_matrix, ConfusionMatrixDisplay (metrics)
      -  Random Forest model
      -  K-Means algorithm
    -  PCA and dendrograms for dimensionality reduction and clustering.

Deep Learning:
  -  TensorFlow: For building and training deep learning models.
  -  Keras (part of TensorFlow): For simplifying model building.
     -  Used layers like:
      -  Dense, Dropout, Conv1D, Conv2D, Flatten, BatchNormalization, Activation, MaxPooling2D.
    -  Utilities:
      -  to_categorical for encoding.
    -  ImageDataGenerator for image augmentation.

Geospatial and Mapping:
  -  Folium: For creating interactive maps (e.g., choropleth maps).

Visualization of Pair Plots and Heatmaps:
  -  sns.pairplot: For analyzing relationships across variables.
  -  sns.heatmap: For visualizing correlation matrices.

Additional Utilities:
  -  operator: For functional-style operations (e.g., sorting or mapping).
  -  glob: For file searching with pattern matching.

# Folders
The project folders are stored in the folder structure:

-  Project Management: Project Brief
-  Data Sets
-  Scripts: Jupyter notebooks containing coding for the analysis
-  Visualizations

# Deliverable

-  Powerpoint Presentations


