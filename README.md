# 🩺 Diabetes Health Indicators Analysis (Big Data Systems)

## 📌 Project Overview
This project was developed for the IT 462: Big Data Systems course at King Saud University. We utilized Apache Spark and Scala to analyze the CDC Diabetes Health Indicators dataset. The project involves processing large-scale healthcare data to uncover patterns and build machine learning models to predict diabetes risk based on lifestyle and health factors.

## 🛠️ Technologies Used
* **Framework:** Apache Spark
* **Language:** Scala
* **Components:** Spark RDDs, Spark SQL, Spark MLlib
* **Domain:** Big Data Analytics, Healthcare Informatics

## 📂 Repository Structure
* `/Scala Code`: Contains all Scala scripts used across the pipeline, including data preprocessing, RDD operations, SQL queries, and machine learning models.
* `/Results`: Output logs, SQL result CSVs, and ML evaluation metrics.
* `Dataset.zip`: The compressed archive containing the original and preprocessed BRFSS 2015 health datasets.
* `Report.pdf`: The final academic report detailing our methodology, analysis, and conclusions.
* `Presentation.pdf`: The presentation slides summarizing the project for review.

## 🚀 Key Phases & Implementation
1. **Data Preprocessing:** Cleaned the raw CDC dataset, handling missing values and casting data types for Spark processing.
2. **RDD & SQL Analysis:** Extracted demographic insights (e.g., correlation between BMI, Age, High Blood Pressure, and Diabetes) using optimized Spark SQL queries and map-reduce RDD transformations.
3. **Machine Learning:** Built scalable classification models using Spark MLlib (StringIndexer, VectorAssembler) to predict the presence of diabetes. Evaluated models based on accuracy and precision metrics.

---
*Group Members: Najla Almazyad, Dalal Alyousef, Jood Alkhrashi, Sara Aloqiel*
