# Healthcare Analytics Project

This project analyzes healthcare utilization patterns using patient demographic and medical data. It explores how factors such as age, income, illness burden, insurance type, and chronic conditions influence doctor visits, reduced activity, and overall healthcare access.

## Project Overview

The analysis is performed in a Jupyter Notebook using Python and data science libraries. It focuses on understanding how different patient characteristics are related to healthcare usage and health outcomes.

### Key questions explored
- How does income affect hospital visits?
- Is there a relationship between age and income?
- Do illness count and chronic conditions influence doctor visits?
- Are there differences in healthcare usage by gender?
- Does insurance coverage affect healthcare access?
- What factors show the strongest correlation with patient visits?

## Dataset

The project uses the dataset:

- `Healthcare Analytics for Doctor.csv`

This dataset includes variables such as:
- `visits`
- `gender`
- `age`
- `income`
- `illness`
- `reduced`
- `health`
- `private`
- `freepoor`
- `freerepat`
- `nchronic`
- `lchronic`

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```bash
HealthcareProject/
├── HealthCare.ipynb
├── Healthcare Analytics for Doctor.csv
├── README.md
```

## Setup

1. Clone the repository.
2. Open the project folder.
3. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `HealthCare.ipynb` and run the cells.

## Analysis Included

- Data loading and inspection
- Handling missing values and duplicate records
- Descriptive statistics
- Correlation analysis
- Data visualizations using charts and heatmaps
- Relationship analysis between patient variables and doctor visits

## Key Findings

The notebook highlights patterns such as:
- income-related differences in healthcare use
- influence of illness burden on doctor visits
- impact of chronic conditions on patient utilization
- gender-based trends in reduced activity and healthcare access
- relationship between insurance coverage and medical visits

## Goals

This project aims to provide a clear understanding of healthcare utilization using exploratory data analysis and data visualization techniques. It is useful for learning data analysis, healthcare insights, and practical Python-based analytics workflows.

## License

This project is for educational and portfolio purposes.

## Author

Neha

## Future Improvements

- Add predictive modeling for patient visit patterns
- Build a dashboard for interactive healthcare analysis
- Perform deeper statistical testing
- Expand the project with additional healthcare datasets
