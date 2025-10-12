# Predictive Maintenance Analysis for Machine Failure Preventio

Predictive maintenance analysis using sensor data and machine learning. This project builds a Random Forest model and a Gradio dashboard to identify high-risk machines for proactive maintenance.

---

## Project Structure

- `data/` — contains datasets used in the analysis (raw, cleaned, processed)  
- `notebooks/` — Jupyter notebooks for data exploration, model building, and dashboard prototyping  
- `requirements.txt` — list of Python dependencies  
- `LICENSE` — the licensing file  
- `README.md` — this documentation  

---

## Features

- Exploratory data analysis and visualization of sensor data  
- Data cleaning, feature engineering, outlier handling  
- Training of a **Random Forest** classifier to detect machines at risk of failure  
- Model evaluation metrics: accuracy, precision, recall, F1 score, ROC curve  
- Gradio-based dashboard for interactive inference / risk scoring  
- Ability to flag high-risk machines to inform maintenance decisions  

---

## Tools & Libraries

- `pandas`, `numpy` - Data handling
- `matplotlib`, `seaborn` - Machine learning 
- `scikit-learn` - Machine learning 
- `gradio` - Interactive dashboard 
- `jupyter` - Notebook environment 

---

## How to Use

### Setup

1. Clone the repository:  
   ```bash
   git clone https://github.com/nurulashraf/predictive-maintenance-analysis-for-machine-failure-prevention.git
   cd predictive-maintenance-analysis-for-machine-failure-prevention
   ````

2. Create a virtual environment (recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate    # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. **Open notebook**

   Launch Jupyter:

   ```bash
   jupyter notebook
   ```

   or

   ```bash
   jupyter lab
   ```

   Then open the notebook in the `notebooks/` folder.

The dashboard allows users to input sensor features and get a risk prediction (e.g. “high risk” or probability) for machine failure.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for full details.

