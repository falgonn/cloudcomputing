# International Mathematical Olympiad (IMO) Data Analysis

This project involves the analysis of data related to the International Mathematical Olympiad (IMO). The dataset includes results from various countries, focusing on team compositions and individual performances. The analysis explores trends such as female representation in teams and the relationship between individual scores and the medals awarded.

## Problem Statement:
The project aims to answer two key questions:

1. **Which countries have consistently shown the highest female representation in their IMO teams?**  
   - This analysis focuses on identifying countries that have maintained a significant percentage of female participants over the years.

2. **What medal can someone win based on total scores?**  
   - Using machine learning techniques like Random Forest, the goal is to predict the type of medal (Gold, Silver, Bronze, or Honourable Mention) based on a participant's total score.

## Project Structure

This repository consists of two branches:

- **`main` branch**: Contains the dataset in CSV format that will be used for the analysis.
- **`master` branch**: Contains the code and analysis scripts, including the Jupyter notebook used to analyze the data.

### Branches:
- `main`:
  - Contains the following files:
    - `IMO_data.csv`: A CSV file containing the results from IMO participants, including countries, scores, gender information, and medals.
    - `team_composition.csv`: A CSV file containing details about the team composition of various countries over the years.
  
- `master`:
  - Contains the following files:
    - `cloud_project.ipynb`: The Jupyter notebook with code for data processing and analysis using PySpark.
    - `data_analysis.py`: Python script that implements machine learning models to predict medal types based on participant scores.
    - `visualization.py`: Python script that generates visualizations of the dataset to show trends like female participation and medal distribution.

## Setup Instructions

### 1. Clone the Repository
To clone the repository, use the following command:

```bash
git clone https://github.com/your-username/IMO-data-analysis.git
```

### 2. Switch to the correct branch
After cloning, ensure you switch to the correct branch based on the files you need to work with:

- For the dataset, switch to the `main` branch:
  ```bash
  git checkout main
  ```

- For the code and analysis, switch to the `master` branch:
  ```bash
  git checkout master
  ```

### 3. Install Required Dependencies

Make sure to have Python 3.x installed. Install the necessary libraries using `pip`:

```bash
pip install -r requirements.txt
```

The `requirements.txt` file includes necessary packages such as:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `pyspark`
- `scikit-learn`

### 4. Run the Code

To run the Jupyter notebook:

1. Navigate to the `master` branch where the Jupyter notebook is located.
2. Launch Jupyter notebook:
   ```bash
   jupyter notebook
   ```
3. Open the `cloud_project.ipynb` notebook and execute the cells for data analysis.

Alternatively, you can run the Python scripts directly:

```bash
python data_analysis.py
python visualization.py
```

### 5. Load the Dataset

Ensure that the CSV files from the `main` branch are available in the same directory as the code or provide the correct path to the files in the code.

## Analysis

- **Female Representation Analysis**: Using the dataset, the proportion of female participants in IMO teams is calculated over time. This is visualized to identify trends across different countries.
  
- **Medal Prediction Model**: A Random Forest model is trained to predict the type of medal a participant can win based on their total score. This model uses the historical data of scores and medals.

- **Visualizations**: Various plots are generated to help visualize:
  - Female participation trends over the years.
  - Relationship between participant scores and medal types.

## Notes

- Ensure that both branches are kept synchronized with the latest data and code.
- Make sure to respect any data privacy and citation requirements when using and sharing the dataset.
  
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Key Notes:
- **Two Branches**: The project is split across two branches (`main` for data, `master` for code). Make sure to switch between branches to access the correct files.
- **Requirements**: Ensure that you have all dependencies installed to run the project code.
- **Run the Jupyter Notebook**: Use Jupyter to explore and analyze the data interactively.

Let me know if you need further modifications!
