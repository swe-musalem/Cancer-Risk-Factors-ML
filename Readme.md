# Cancer-risk-ml

# Cancer Risk Factors Analysis and Prediction

## Project Title
**Cancer Risk Factors Analysis and Prediction Using Machine Learning**

## Motivation

### Why This Problem?

Cancer remains one of the leading causes of death worldwide, with millions of new cases diagnosed each year. Early detection and risk assessment are crucial for effective treatment and improved patient outcomes. Understanding the various risk factors that contribute to cancer development can help in:

- **Preventive Healthcare**: Identifying high-risk individuals before cancer develops
- **Early Intervention**: Enabling timely medical intervention and lifestyle changes
- **Resource Allocation**: Helping healthcare systems prioritize screening programs
- **Public Health Policy**: Informing evidence-based health policies and awareness campaigns

### Why This Dataset?

The Cancer Risk Factors Dataset provides a comprehensive collection of variables that are scientifically linked to cancer development, including:

- **Lifestyle Factors**: Smoking, alcohol consumption, exercise habits, diet patterns
- **Demographic Factors**: Age, gender
- **Environmental Factors**: Pollution exposure
- **Genetic Factors**: Family history of cancer
- **Physical Health Indicators**: BMI

### Key Benefits:

1. **Real-world Impact**: Direct application to healthcare and preventive medicine
2. **Multi-factorial Analysis**: Comprehensive view of various cancer risk contributors
3. **Actionable Insights**: Results can guide individual lifestyle changes and public health initiatives
4. **Scalability**: Model can be applied to large populations for risk screening
5. **Cost-effective**: Early risk identification can reduce healthcare costs by preventing advanced-stage cancer treatments

### Research Questions Addressed:

- Which risk factors are most strongly associated with cancer development?
- Can we predict cancer risk levels based on lifestyle and demographic factors?
- How do different combinations of risk factors interact to influence cancer probability?
- What are the most effective intervention points for cancer prevention?

This project aims to leverage machine learning techniques to build predictive models that can assist healthcare professionals and individuals in making informed decisions about cancer prevention and early detection strategies.

## Team

- Musallam Alodssari 443101087
- Yazeed Alqarni 444101099


## Quick start

Prerequisites: Python 3.8+

1. Create and activate a virtual environment

- Windows (PowerShell):
  ```ps
  python -m venv env
  .\env\Scripts\Activate.ps1
  ```
- Windows (cmd):
  ```cmd
  python -m venv env
  .\env\Scripts\activate.bat
  ```
- macOS / Linux:
  ```sh
  python3 -m venv env
  source env/bin/activate
  ```

2. Install packages
```sh
pip install --upgrade pip
pip install pandas scikit-learn jupyter notebook matplotlib seaborn
```



Files of interest:
- cancer-risk-factors.csv
- preproccess.ipynb