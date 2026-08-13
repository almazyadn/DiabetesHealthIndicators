# 🩺 Diabetes Health Indicators Analysis (Big Data Systems)

## 📌 Project Overview
This project was developed for the IT 462: Big Data Systems course at King Saud University. We utilized Apache Spark and Scala to analyze the CDC Diabetes Health Indicators dataset. The project involves processing large-scale healthcare data to uncover patterns and build machine learning models to predict diabetes risk based on lifestyle and health factors.

## 🛠️ Technologies Used
* **Framework:** Apache Spark
* **Language:** Scala
* **Components:** Spark RDDs, Spark SQL, Spark MLlib
* **Domain:** Big Data Analytics, Healthcare Informatics

## 📂 Repository Structure
* `/code`: Contains the Scala scripts divided into phases:
  * `01_DataPreprocessing.scala`: Data cleaning and transformation.
  * `02_RDDOperations.scala`: Low-level data manipulation using RDDs.
  * `03_SQLOperations.scala`: Querying and aggregations using Spark SQL.
  * `04_MachineLearning.scala`: Predictive modeling using Spark MLlib.
  * `utility_functions.scala`: Helper functions used across the pipeline.
* `/data`: The original and preprocessed BRFSS 2015 health datasets.
* `/docs`: Contains the final academic report and presentation slides.
* `/results`: Output logs, SQL result CSVs, and ML evaluation metrics.

## 🚀 Key Phases & Implementation
1. **Data Preprocessing:** Cleaned the raw CDC dataset, handling missing values and casting data types for Spark processing.
2. **RDD & SQL Analysis:** Extracted demographic insights (e.g., correlation between BMI, Age, High Blood Pressure, and Diabetes) using optimized Spark SQL queries and map-reduce RDD transformations.
3. **Machine Learning:** Built scalable classification models using Spark MLlib (StringIndexer, VectorAssembler) to predict the presence of diabetes. Evaluated models based on accuracy and precision metrics.

---
*Group Members: Najla Almazyad, Dalal Alyousef, Jood Alkhrashi, Sara Aloqiel*
