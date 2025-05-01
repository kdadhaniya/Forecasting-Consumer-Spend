# Forecasting California's Economic Response to Wildfires

### Context
In recent years, California has experienced increasingly severe wildfires. Beyond the environmental and human toll, these disasters have disrupted the economy—affecting housing prices, consumer spending, and infrastructure demand. Understanding and forecasting these effects is critical for policymakers, insurers, investors, and emergency planners.

---

### Problem Statement
You are a data scientist at a policy research center. Your task is to assess how California's economy responds to wildfire damage and to develop a machine learning model that can predict economic impact based on the severity of wildfires.

Using real data from 2014 to 2023, your goal is to answer:

**Can wildfire data be used to forecast economic outcomes and identify industries that rebound or grow following wildfire events?**

---

### Provided Datasets

1. **California Wildfire Damage (2014–2023)**
   Contains yearly data on acres burned, homes destroyed, fatalities, and estimated financial losses.

2. **Personal Consumption Expenditures (PCE) (1997–2023)**
   Contains consumer spending by category, including durable goods, healthcare, and construction.

3. **Housing Price Index (HPI) (1991–2023)**
   Contains monthly housing price index data, which will be aggregated by year.

---

### Your Objectives

- Clean, merge, and explore the datasets.
- Train machine learning models to predict:
  - Housing Price Index (HPI)
  - Personal Consumption Expenditures (PCE)
- Cluster years based on wildfire damage and analyze recovery profiles.
- Use PCA to reduce dimensionality and visually interpret economic patterns.
- Summarize findings with insights relevant for public planning and investment.
---

### Example solution Summary

In our example solution:
- Gradient Boosting models accurately predicted HPI and PCE.
- The most predictive features were **fatalities** and **financial loss**.
- KMeans clustering grouped years into distinct economic recovery types.
- PCA validated visual separation between year types.
- Post-wildfire rebounds were especially notable in:
  - Durable goods
  - Healthcare and pharmaceuticals
  - Construction and housing sectors




### Running the IPYNB File

Follow the below steps to start running and working with the IPYNB file:
- Download the project from GitHub as a zip folder
- Unzip the folder
- Open the folder with an IDE (i.e. VSCode, PyCharm)
- in the IDE terminal, type the following to create a virtual environment: **python3 -m venv venv**
- To activate the virtual environment, do one of the following:
  - macOS/Linux: **source venv/bin/activate**
  - Windows: **venv\Scripts\Activate**
- Once virtual environment is activated, run the following commands to install the libraries from the requirements.txt file:
  - **pip install --upgrade pip**
  - **pip install -r requirements.txt**
- Once libraries are downloaded, you can run the IPYNB file and play around with the code
