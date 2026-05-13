# API-JSON-to-DataFrame Project

A structured and reproducible **API Data Extraction and Transformation Pipeline** implemented using Python and Jupyter Notebooks.

---

## Project Objective

The primary objective of this project is to demonstrate a systematic approach to retrieving data from public API endpoints, transforming JSON responses into structured tabular datasets using the pandas library, and exporting the processed data as CSV files suitable for reporting and downstream analysis.

---

## Project Structure

The following files are organized sequentially, with each notebook accompanied by its corresponding CSV output:

| # | File | Description |
|---|------|-------------|
| 01 | `01_Api_json_dataframe_hospital-project.ipynb` | Hospital data extraction notebook |
| 02 | `02_Patient_data.csv` | Exported patient dataset |
| 03 | `03_carts_endpoint.ipynb` | Carts API endpoint notebook |
| 04 | `04_carts_endpoint.csv` | Exported carts dataset |
| 05 | `05_Dummy.python_assignment.ipynb` | Dummy data assignment notebook |
| 06 | `06_dummy_data.csv` | Exported dummy dataset |
| 07 | `07_products_endpoint.ipynb` | Products API endpoint notebook |
| 08 | `08_products_data.csv` | Exported products dataset |
| 09 | `09_Staff_assignment.ipynb` | Staff data assignment notebook |
| 10 | `10_employees-3.csv` | Exported employees dataset |

---

## Methodology

Each notebook follows a consistent, step-by-step data processing workflow:

1. **API Request** — Submission of HTTP requests to designated API endpoints.
2. **JSON Parsing** — Parsing and deserialization of JSON response payloads.
3. **DataFrame Construction** — Normalization of structured data into pandas `DataFrame` objects.
4. **Data Quality Checks** — Execution of preliminary inspections including shape validation, column review, data previews, and null value assessment.
5. **CSV Export** — Export of the finalized dataset using `DataFrame.to_csv()`.

---

## Technologies Used

| Tool / Library | Purpose |
|----------------|---------|
| Python 3.x | Core programming language |
| Jupyter Notebook | Interactive development environment |
| pandas | Data manipulation and DataFrame operations |
| requests | HTTP requests to API endpoints |
| json | JSON parsing and deserialization |

---

## Getting Started

### Prerequisites

Ensure the following are installed in your environment:

```bash
pip install pandas requests jupyter
```

### Running the Notebooks

1. Clone or download this repository.
2. Navigate to the project directory.
3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open any `.ipynb` file and run cells sequentially from top to bottom.

---

## Output

Each notebook produces a clean, analysis-ready `.csv` file saved to the project directory. These datasets can be used directly for reporting, visualization, or further statistical analysis.

---

## Project Significance

This project serves as a practical demonstration of core data engineering competencies, including:

- **API Integration** — Connecting to and consuming public REST API endpoints.
- **Data Wrangling** — Transforming raw JSON into structured, normalized datasets.
- **Pipeline Reproducibility** — Notebook-based steps ensure full transparency and repeatability.
- **Data Export** — Producing clean CSV outputs ready for downstream use.

