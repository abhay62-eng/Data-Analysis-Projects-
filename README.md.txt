# IPL Analysis Project

## Overview

This project performs exploratory data analysis (EDA) on Indian Premier League (IPL) cricket match data using Python. The notebook analyzes match statistics, overs, cities, seasons, and other IPL-related insights with the help of data visualization and data processing libraries.

## Project File

* `IPL-Analysis.ipynb` — Main Jupyter Notebook containing the complete analysis.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib

## Libraries Imported

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
```

## Dataset

The project uses an IPL dataset stored in CSV format.

Example:

```python
df = pd.read_csv("IPL.csv", encoding='latin-1')
```

## Analysis Performed

The notebook includes:

* Data loading and inspection
* Dataset information and statistical summary
* Overs analysis
* City-wise match analysis
* Year-wise IPL match analysis
* Frequency and count-based visualizations
* Exploratory data analysis using Pandas

## Key Operations

### Dataset Information

```python
df.info()
df.describe()
```

### Overs Distribution

```python
df['over'].value_counts()
```

### City-wise Match Counts

```python
df['city'].value_counts().head(10)
```

## How to Run the Project

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project directory:

```bash
cd <project-folder>
```

3. Install required libraries:

```bash
pip install pandas numpy matplotlib
```

4. Open the notebook:

```bash
jupyter notebook IPL-Analysis.ipynb
```

## Output

The notebook generates:

* Statistical summaries
* Frequency distributions
* IPL trend analysis
* Graphical visualizations

## Future Improvements

* Add advanced visualizations using Seaborn or Plotly
* Build predictive models for IPL match outcomes
* Add player-level performance analysis
* Create dashboards for interactive analysis

## Author

Created for IPL data exploration and cricket analytics practice.
