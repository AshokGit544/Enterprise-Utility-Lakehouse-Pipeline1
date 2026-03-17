# Enterprise Utility Lakehouse Pipeline

## Project Overview
This project shows a utility-style enterprise data engineering pipeline built using PySpark in Google Colab.

It simulates the kind of work done in a large utility environment where data comes from multiple systems like:
- customer systems
- smart meter systems
- outage systems
- weather systems
- billing and SAP FICO style finance systems

The pipeline processes the data through:
- Bronze layer for raw data
- Silver layer for cleaned data
- Gold layer for business-ready integrated data

This project also prepares AI-ready records for future semantic search, embeddings, and LLM-based use cases.

---

## Business Goal
The goal of this project is to show how enterprise utility data can be:
- ingested from multiple sources
- cleaned and standardized
- integrated using common keys
- published into business-ready datasets
- prepared for analytics, forecasting, and AI-ready retrieval

---

## Tools Used
- Python
- PySpark
- Apache Spark
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## Data Sources Simulated
This project creates sample datasets for:
- customers
- assets
- smart meter usage
- outages
- weather
- billing
- SAP FICO style financial records

---

## Architecture
### Bronze Layer
Stores raw ingested data exactly as received.

### Silver Layer
Stores cleaned and standardized data after:
- null handling
- duplicate removal
- type conversion
- basic quality checks

### Gold Layer
Stores integrated business-ready data using common keys like:
- customer_id
- event_date
- region

This layer supports:
- reporting
- analytics
- forecasting
- AI-ready semantic data preparation

---

## Key Features
- raw data generation
- PySpark ingestion pipeline
- Bronze, Silver, Gold layers
- common-key integration
- data quality checks
- KPI generation
- forecasting-ready features
- AI-ready semantic text preparation
- outage risk ML example

---

## Example Business Value
This project demonstrates how a utility company can improve:
- data quality
- data integration
- reporting reliability
- faster refresh cycles
- forecasting readiness
- AI and semantic retrieval readiness

---

## How to Run
1. Open the notebook in Google Colab
2. Run each cell in order
3. Check generated files in the `outputs` folder
4. Review Bronze, Silver, and Gold outputs
5. Use screenshots for GitHub documentation

---

## Output Files
The pipeline creates:
- `regional_kpis.csv`
- `enterprise_gold_sample.csv`
- `pipeline_summary.json`

---

## Future Improvements
In the next version, this project can be extended with:
- Airflow DAG
- FAISS vector search
- embeddings
- Streamlit dashboard
- GitHub Actions CI/CD
- Delta Lake support

## Author
Ashok Ajmeera
