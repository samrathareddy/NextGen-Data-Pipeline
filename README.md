# Reusable ETL Framework with Airflow 🚀

An **end-to-end data pipeline project** built using Apache Airflow, Docker, and GCP to demonstrate modern data engineering practices. This project simulates real-world ETL workflows to extract, transform, and load data efficiently and reliably.

---

## 🧰 Tech Stack

- **Apache Airflow** – workflow orchestration
- **Docker** – containerization
- **Python** – core development
- **Google Cloud Platform (GCP)** – data storage and compute (BigQuery, GCS)
- **Pandas, SQLAlchemy** – data manipulation and access
- **GitHub Actions** – CI/CD pipeline to run DAGs

---

## 📁 Project Structure

```
NextGen-Data-Pipeline/
│
├── dags/                    # Airflow DAGs directory
│   ├── dag_ETL.py           # Core ETL pipeline DAG
│   └── dag_GCP_Test.py      # Sample test DAG for GCP
│
├── utils/                   # Utility Python modules
│   ├── ETL_functions.py     # Custom Python functions used in DAGs
│   └── __init__.py
│
├── Dockerfile               # Airflow container config
├── docker-compose.yaml      # Multi-container orchestration
├── requirements.txt         # Python dependencies
├── .env                     # Environment variables
├── main.py                  # DAG trigger or entry point
└── README.md
```

---

## 🚦 How It Works

1. **DAG Scheduling**: Airflow schedules the ETL DAG.
2. **Data Extraction**: Reads data from GCS or local CSV.
3. **Transformation**: Uses Pandas to clean and prep data.
4. **Load**: Pushes data into BigQuery (or logs locally for demo).
5. **CI/CD**: GitHub Actions triggers DAGs on code push.

---

## 🛠️ Setup & Run Locally

```bash
# Clone repository
git clone https://github.com/samrathareddy/NextGen-Data-Pipeline.git
cd NextGen-Data-Pipeline

# Start Airflow with Docker
docker-compose up --build
```

Access Airflow UI at: [http://localhost:8080](http://localhost:8080)

---

## 📸 Screenshots

> Add screenshots of Airflow UI, DAG execution, and data preview here.

---

## 📬 Contact

**Samratha Reddy**  
📧 samrathareddy2001@gmail.com  
🌐 [GitHub](https://github.com/samrathareddy)

---
