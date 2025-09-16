[English](./README.md) | [Português](./README-pt.md)

# Data Analysis Course Projects

This repository contains all projects developed as part of my Data Analysis career path.  
Each project covers a specific topic such as SQL, data cleaning, visualization, and exploratory analysis.  


## Repository Structure
- [`project-01-student-mental-health/`](./project-01-student-mental-health/) → SQL fundamentals and practice queries  

## How to Use
1. Install [Python 3.9+](https://www.python.org/downloads/) if not already installed.  
2. Clone the repository to your local machine:
```git clone https://github.com/vsrromero/data-analysis-course-projects.git```
3. Navigate to the project folder you are interested in:
```cd data-analysis-course-projects/project-01-student-mental-health```
4. (Optional but recommended) Create a virtual environment:
```
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```
5. Install the required Python packages:

```
pip install duckdb ipykernel numpy pandas
```
6. (Recommended for VS Code users) Install the Rainbow CSV extension to easily view, filter, and manipulate CSV files, which are frequently used in the projects of this repository as data sources for exploratory analysis, cleaning, and visualization:
https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv

7. Open the Jupyter notebook (.ipynb) in VS Code or any Jupyter environment.
8. Run the notebook cells. The SQL queries use DuckDB to query CSV files directly.
8. Check the outputs/ folder for CSV results.
