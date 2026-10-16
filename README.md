# Graduate Employment Analytics Web Application

## Project Description
An end-to-end data pipeline and analytics dashboard designed to process and visualize post-graduate employment metrics across universities. System architecture highlights include:
- Ingestion & Storage: Raw University Graduate Data stored in AWS S3
- Pipeline & Processing: Various metric extractions and batch aggregation
- API & Backend: Analytics endpoints
- Interactive Dashboards: Frontend interface providing table and chart comparisons, filters by institution or degree and forecasting salary trends

## Prerequisites

- Python 3.12.3

### Setting Up a Virtual Environment

1. **Create a virtual environment** in your project directory:

```bash
py -3.12 -m venv .venv
```

2. Activate it

```bash
# Windows
.venv\Scripts\activate
# Linux Ubuntu
source venv/bin/activate
```

3. Install required packages

```bash
pip install -r requirements.txt
```

4. Run the Flask app.

```bash
sudo python3 src/app.py
```
