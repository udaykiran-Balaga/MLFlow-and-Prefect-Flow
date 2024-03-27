# Project Overview:
I analyzed a dataset of review text and review titles from a diverse range of sources and used Python along with popular libraries like pandas, scikit-learn, MLflow, and Prefect to build a machine learning pipeline.

# Techniques Used:

Data Cleaning: Handled missing values and converted text to lowercase for consistency.
Feature Engineering: Extracted input-output pairs and split the data for training and testing.
Text Vectorization: Utilized CountVectorizer to transform text data into a numerical format.
Data Scaling: Employed MinMaxScaler to scale the data for better model performance.
Model Training: Trained a Decision Tree Classifier with hyperparameters tuning for accurate predictions.
Model Evaluation: Evaluated the model using metrics like accuracy score to assess its performance.

# MLflow Integration:

# Experiment Tracking: 

Leveraged MLflow to log and compare model runs, metrics, and parameters, enabling easy experimentation and optimization.
Model Serialization: Saved the best model as an MLflow registered model, making it easy to deploy and use in production.
Graphical Analysis: Visualized model performance and training progress using MLflow's tracking capabilities, gaining insights for further improvements.
Prefect Integration:

# Dataflow Orchestration: 

Used Prefect to orchestrate the entire machine learning pipeline, ensuring seamless execution of tasks and handling dependencies.
Task Modularity: Defined Prefect tasks for each step of the pipeline, from data loading to model evaluation, ensuring modularity and reusability.
Dashboard Monitoring: Utilized the Prefect dashboard to monitor the progress of the pipeline, track task dependencies, and troubleshoot any issues that arise.

# Key Learnings:

Importance of data preprocessing for effective machine learning models.
Hands-on experience with scikit-learn, MLflow, and Prefect for building robust ML pipelines.
Understanding of hyperparameter tuning for improving model performance.

# Results:
Achieved an impressive testing accuracy of 84% which demonstrates the effectiveness of the model in predicting sentiment from review titles.


#MachineLearning #DataScience #SentimentAnalysis #DecisionTreeClassifier #Python #MLflow #Prefect #MLPipelines
