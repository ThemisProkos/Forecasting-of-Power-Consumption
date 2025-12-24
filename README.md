

# Time-Series Forecasting of Residential Energy Consumption

This repository contains the final project for a Machine Learning course, focused on time-series forecasting of residential energy consumption using multivariate 
sensor data. The goal is to analyze, preprocess, and model energy usage patterns and evaluate the performance of different forecasting approaches.

---

## Project Overview

Accurate energy consumption forecasting is essential for energy efficiency, demand-side management, and smart grid applications. In this project, historical data from household sensors is used to predict appliance energy consumption over time.

The project covers:
- Exploratory data analysis (EDA)
- Data preprocessing and feature analysis
- Time-series modeling and forecasting
- Model evaluation and comparison

---

## Dataset

The dataset used is **Energy Efficiency Dataset** containing measurements from a residential building, including:

- Appliance and lighting energy consumption
- Indoor temperature and humidity (multiple rooms)
- Outdoor weather conditions (temperature, humidity, wind speed, pressure)
- Time-stamped observations at 10-minute intervals

**Dataset file:**


**Size:**  
- ~19,735 samples  
- 29 variables

---

## Methodology

The project follows a complete time-series analysis pipeline:

1. **Data Understanding**
   - Time granularity and duration analysis
   - Variable description and correlation inspection

2. **Data Preprocessing**
   - Handling missing values
   - Outlier detection
   - Feature inspection and cleaning
   - Creating new features from the initial dataset (Feature Extraction)
   - Additing lagging values of the consuption in every observation
   - Additing rolling means values in every observation 

3. **Exploratory Analysis**
   - Time-series visualization
   - ACF and PACF analysis
   - Trend and seasonality inspection

4. **Modeling**
   - Classical time-series models
   - Regression-based approaches
   - Forecast generation and comparison

5. **Evaluation**
   - Error metrics
   - Visual comparison of predictions vs actual values

All steps are implemented and documented in the provided Jupyter notebook.

---

## Repository Structure

```text
energy-consumption-time-series-forecasting/
├── energydata_complete.csv              # Dataset
├── Team_26_final_project_ML.ipynb       # Jupyter notebook (analysis + models)
├── TEAM_26_Final_Project.pdf            # Final project report
└── README.md                            # Project documentation


```

## How to Run the Project

1. Clone the repository:

```text
git clone https://github.com/yourusername/energy-consumption-time-series-forecasting.git

```
2. Install required Python packages:

```text

pip install numpy pandas matplotlib seaborn statsmodels scikit-learn
```
3. Open the notebook:

```text
   jupyter notebook Team_26_final_project_ML.ipynb

```

4.Run the cells sequentially to reproduce the analysis and results.

## Results

The models demonstrate the feasibility of forecasting short-term residential energy consumption using historical sensor data. Results highlight the 
importance of temporal dependencies, seasonality, and feature selection in time-series prediction tasks.The most reliable models were proven to be the deep learing alogrithms while the machine learning models 
performed good as well.

Detailed analysis and conclusions are provided in the final project report.

## Citation

If you use this work in your research, please cite:

```bibtex
@mastersthesis{author2024,
  title={Time-Series Forecasting of Residential Energy Consumption},
  author={[Themistoklis Proko]},
  school={[University of Thessaly]},
  year={2025},
  url={[https://github.com/[your-username]/[repository-name]](https://github.com/ThemisProkos/Forecasting-of-Power-Consumption)}
}

```

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### License Overview
- **Commercial use**: Allowed
- **Modification**: Allowed
- **Distribution**: Allowed
- **Private use**: Allowed
- **Inclusion in other projects**: Allowed

### Requirements
- Include the original copyright notice
- Include the license text

### Limitations
- No warranty or liability

The MIT License is a permissive license that allows others to use your code with minimal restrictions, making it ideal for academic and research projects.

---

## Contact
**Your Name**  
- 📧 Email: [themisproko@gmail.com]  
- 💼 LinkedIn: [https://www.linkedin.com/in/themistoklis-proko-108638287/] 
- 💻 GitHub: [https://github.com/ThemisProkos] 
- 🎓 Institution: University of Thessaly  

*Feel free to reach out for collaborations, questions about the methodology, or discussions about power system inertia estimation.*



