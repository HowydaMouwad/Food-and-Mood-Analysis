# Nutrition and Mood Analysis

This project explores the relationship between nutrition and mood levels. It analyzes how different food components (such as calories, fat, sugar, protein, etc.) affect people's mood and energy levels, based on a dataset that includes information on various food items and their associated nutrition.

## Project Overview

The goal of this project is to:
- Clean and preprocess the data.
- Explore relationships between various nutritional factors and mood.
- Analyze correlations and insights through visualizations.
- Build a report with key findings.

## Dataset

The dataset used in this project contains nutritional information about various food items and user-reported mood levels, energy levels, and other attributes like body type. It includes columns like:

- **Product Name**: The name of the food item.
- **Calories**: The number of calories per serving.
- **Body Type**: Categorized as Fat, Slim, Balanced.
- **Mood**: User-reported mood, with a numerical scale (0 to 10).
- **Energy**: User-reported energy level.
- **Total Fat**: Amount of fat in grams.
- **Total Sugars**: Amount of sugar in grams.
- **Carbohydrates (Carbs)**: Amount of carbohydrates in grams.
- **Protein**: Amount of protein in grams.

## Steps Involved

1. **Data Cleaning and Preprocessing**:
    - Handle missing values.
    - Convert categorical variables to numerical (e.g., Body Type).
    - Normalize or scale the data where necessary.
    
2. **Exploratory Data Analysis (EDA)**:
    - Analyze the distribution of nutritional data.
    - Visualize relationships between different variables (e.g., mood vs. total fat, mood vs. sugar).
    - Check for correlations and outliers.

3. **Insights**:
    - Key insights about how different nutrients correlate with mood and energy levels.
    - Identification of any patterns or trends.

4. **Visualization**:
    - Scatter plots, box plots, and correlation matrices to highlight relationships.
    
5. **Conclusion**:
    - Summary of the analysis and potential suggestions for improving mood and energy through dietary changes.

## Tools Used

- **Python**: For data manipulation and analysis.
- **Pandas**: For data handling and cleaning.
- **Matplotlib and Seaborn**: For visualization and plotting.
- **Scikit-learn**: For encoding categorical variables.

## Getting Started

To run this project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/nutrition_mood_analysis.git
    cd nutrition_mood_analysis
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook or Python script to execute the analysis.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Kaggle for providing the dataset.
- Python community for the amazing open-source libraries.

