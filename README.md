### 📊 Anomaly Detection Project as ETL:

My project follows a standard data pipeline workflow, which can be mapped to the Extract, Transform, Load (ETL) framework.

| My Code Section         | ETL Phase         | Description                                                               |
| :---------------------- | :---------------- | :------------------------------------------------------------------------ |
| `import`                | **Extract** | Pulling raw data from its source (CSV, database, etc.).                   |
| `extract the features`  | **Transform** | Cleaning, preprocessing, and feature engineering to prepare data for modeling. |
| `train the models` & `save results` | **Load** | Saving the trained model or the final predictions for later use. |


<h3>Extract</h3>

The data in imported from a **CSV** file to a **Pandas Dataframe**.

<h3>Tranform</h3>

In the transformation phase, a multi-step data preprocessing pipeline is executed. This process starts with a thorough **data cleaning** step to handle missing values and correct invalid entries. This ensures the data meets the quality standards necessary for training accurate and reliable machine learning models.
- **Data Cleaning:**
    - **Exploration**: My data exploration begins with a preliminary inspection of the dataset. I use the **Pandas .info()** method to quickly identify key characteristics like **data types**, **the number of non-null values**, and **overall memory consumption**, which informs the subsequent data cleaning and transformation steps.
 
    - **Transforming non-numerical to numerical** features unsing **one-hot-encoding** in **Pandas**

