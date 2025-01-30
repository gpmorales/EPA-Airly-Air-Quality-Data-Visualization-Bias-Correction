# EPA-Airly-Air-Quality-Data-Visualization-Bias-Correction (ML)

### Project Overview
Developed a cost-effective air quality monitoring solution that achieves 95% accuracy compared to EPA federal monitors at 1/500th of the cost. The project integrates data from Airly® sensors with EPA federal monitor readings to create a reliable, affordable air quality measurement system.

### Technical Implementation
* **Data Processing**: Used Pandas and SciKit-Learn to analyze data from:
  - Airly® sensor fleet
  - EPA federal monitors

* **Machine Learning Model**:
  - Implemented linear regression using SciKit-Learn
  - Created bias correction model using EPA data as reference
  - Applied correction coefficients to raw Airly® readings

* **Data Visualization**:
  - Generated visual representations using Matplotlib & Seaborn
  - Created business-ready graphics for stakeholder presentations

* **Data Management**:
  - Custom CSV/Excel file handler (SensorMerger.py)
  - Consolidated multiple excel sheets into unified data frames

### Key Features
* 95% accuracy rate compared to EPA monitors
* Significant cost reduction (1/500th of standard monitors)
* Automated data processing pipeline
* Business-focused visualization outputs

### Dependencies
* Python
* Pandas
* SciKit-Learn
* Matplotlib
* Seaborn
* Excel/CSV handling libraries

---
© 2025 George Morales - Air Quality Monitoring Project
