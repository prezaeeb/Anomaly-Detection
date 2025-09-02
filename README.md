### 📊 Anomaly Detection Project as ETL:

My project follows a standard data pipeline workflow, which can be mapped to the Extract, Transform, Load (ETL) framework.

| My Code Section         | ETL Phase         | Description                                                               |
| :---------------------- | :---------------- | :------------------------------------------------------------------------ |
| `import`                | **Extract** | Pulling raw data from its source (CSV, database, etc.).                   |
| `extract the features`  | **Transform** | Cleaning, preprocessing, and feature engineering to prepare data for modeling. |
| `train the models` & `save results` | **Load** | Saving the trained model or the final predictions for later use. |


<h3>Extract</h3>

The data in imported from a **CSV** file to a **Pandas Dataframe**.

