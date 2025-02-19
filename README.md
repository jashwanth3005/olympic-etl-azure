# 🏅 Olympic ETL Pipeline on Azure

## 📌 Project Overview
This project extracts, transforms, and loads (ETL) the **Olympic dataset** from GitHub using **Azure Data Factory**, processes it in **Databricks (PySpark)**, and stores the transformed data in **Azure Data Lake Storage Gen2**.

## 🏗️ **Architecture**
1️⃣ **Extract**: Data is fetched from **GitHub** using **Azure Data Factory (ADF)**  
2️⃣ **Transform**: Data is processed and cleaned using **Databricks + PySpark**  
3️⃣ **Load**: Processed data is stored in **Azure Data Lake Storage Gen2 (ADLS Gen2)**  

## 🔧 **Technologies Used**
- **Azure Data Factory (ADF)** → For data extraction  
- **Azure Data Lake Storage Gen2 (ADLS Gen2)** → For raw & processed data storage  
- **Azure Databricks (PySpark)** → For data transformation  
- **GitHub** → For version control and project management  

## 🚀 **How to Run the Pipeline**
1️⃣ **Clone this repository**:
   ```sh
   git clone https://github.com/jashwanth3005/olympic-etl-azure.git
