# Carbon footprint Calculator

## 📖 Project Overview
This is an interactive web application developed with **Streamlit** that allows users to estimate their personal carbon footprint based on daily lifestyle habits.

## ⚙️ Methodology & Features
The application processes user inputs against a database of country-specific **Emission Factors (EF)**, which was sourced from EcoInvent.

### Calculation Logic
User inputs (daily/weekly/monthly) are normalized to **annual values** before processing:
$$\text{Total Emissions (tonnes)} = \frac{\sum(\text{Activity}_{\text{annual}} \times \text{EF})}{1000}$$


## Interface

<img width="1830" height="773" alt="image" src="https://github.com/user-attachments/assets/c91d7c7e-98bc-4581-aaf6-c24b7ee5bdd1" />


## 🛠️ Tech Stack
* **Framework:** Streamlit (Python).
* **Deployment:** Web-based interface.

---
*Repository contains the application source code (`carbon_calculator.py`).*
