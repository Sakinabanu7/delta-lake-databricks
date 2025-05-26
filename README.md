# 🧪 Delta Lake on Databricks – GCS Integration
 
A cloud-native data engineering pipeline built using Apache Spark on Databricks with Google Cloud Storage (GCS).  

This project demonstrates a complete Delta Lake workflow, including data ingestion, ingestion timestamping, Delta table creation, UPSERT operations via `MERGE`, and querying historical data through time travel. Ideal for real-world analytics and ETL use cases.

---

## 🚀 Features Covered

- 🔐 GCS authentication via service account
- 📥 Reading CSV data from GCS using PySpark
- 🕒 Adding ingestion timestamp columns
- 💾 Writing data in Delta format
- 🔁 Performing UPSERT operations using Delta MERGE
- ✂️ Updating only selected columns (e.g., `Quantity`, `TotalPrice`)
- 📜 Auditing changes using the Delta table history
- ⏳ Querying older versions using time travel
- 📦 Simulating Day 2 incremental loads

---

## 📂 File Structure

| File Name                  | Description                                      |
|---------------------------|--------------------------------------------------|
| `delta_lake_notebook.py`  | Databricks code for the complete Delta workflow |
| `README.md`               | Project overview and documentation               |
| *(Optional)* `Orders.csv` | Sample dataset used for ingestion                |

---

## 🛠️ Tools & Technologies

- **Apache Spark** (PySpark)
- **Delta Lake**
- **Databricks** (Notebook environment)
- **Google Cloud Storage (GCS)**

---

## 🧠 Learning Outcomes

This project helped me gain hands-on experience in:

- Connecting Databricks with GCS using service account credentials
- Ingesting structured data efficiently with timestamping
- Using Delta Lake's powerful merge logic for incremental updates
- Tracking all changes with version history
- Querying previous states of data using time-based and version-based filters

---


## 🙋‍♀️ Author

**Sakina Banu**  
🎓 Postgraduate Student – Global Business Management  
💻 Data Engineering & Cloud Enthusiast  
🔗 [LinkedIn Profile] [www.linkedin.com/in/sakina-banu-018449247]


---

## 🔗 Project Link

GitHub Repository: [https://github.com/Sakinabanu7/delta-lake-databricks](https://github.com/Sakinabanu7/delta-lake-databricks)

---

⭐️ Feel free to fork, clone, or share. Feedback is welcome!

