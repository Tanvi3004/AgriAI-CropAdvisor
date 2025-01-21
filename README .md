
# Precision Farming: Optimizing Agricultural Productivity

Project Overview: 
This project leverages data science and machine learning techniques to optimize agricultural productivity by analyzing soil and climatic conditions. The system provides recommendations for the best crops to grow based on environmental factors, helping farmers make data-driven decisions for precision farming.

![Image](https://github.com/user-attachments/assets/9862aa60-fa46-4b59-9162-058f0a00cf13)



# Project Overview: 
This project leverages data science and machine learning techniques to optimize agricultural productivity by analyzing soil and climatic conditions. The system provides recommendations for the best crops to grow based on environmental factors, helping farmers make data-driven decisions for precision farming.

## Installation / how to use?

1. Clone the repository:
```bash
git clone https://github.com/Tanvi3004/AgriAI-CropAdvisor.git
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Open Jupyter Notebook:
4. Run the Notebook:
Execute each cell in sequential order by selecting the cell and pressing Shift + Enter.
You can modify the input data (e.g., soil and climate parameters) in the designated cell to test predictions for various conditions.
View data visualizations, cluster analysis, and prediction results directly in the notebook.

## What This Project Does

### 1. Data Exploration and Analysis
- Dataset:The system uses a dataset containing soil nutrients (Nitrogen, Phosphorus, Potassium), climatic factors (Temperature, Humidity, Rainfall), and soil pH for various crops.
- Insights:Detailed statistics for each crop, including required soil nutrients and environmental conditions. Visualizations to understand the distribution of soil and climate parameters.
### 2. K-Means Clustering
- Purpose: Group crops into clusters based on similar soil and climatic requirements.
- Process:
  - Elbow Method: Determines the optimal number of clusters.
- Clustering: Assigns crops to specific clusters for better categorization.
- Outcome: Identifies groups of crops with similar environmental needs, aiding targeted recommendations.
### 3. Logistic Regression for Crop Prediction
- Goal: Predict the most suitable crop for given soil and climatic conditions.
- Steps:
  - Train-Test Split: Splits the dataset into training and testing sets.
- Model Training: Uses Logistic Regression to learn crop classification.
- Evaluation: Provides classification metrics for model performance.
- Prediction:
  - Input: Parameters like Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, and Rainfall.
  - Output: Suggests the best crop based on the input conditions.
### 4. Interactive Analysis
- Interactive widgets allow users to explore crop-specific requirements, 
- such as:
  - Minimum, average, and maximum values for soil nutrients and climatic factors. Comparison of environmental needs across crops.

## How to use?

1. Clone the repository:

```bash
 git clone https://github.com/Tanvi3004/AgriAI-CropAdvisor.git
```
2. Install dependencies:

```bash
pip install -r requirements.txt

```
3. Open Jupyter Notebook:

```bash
 git clone https://github.com/Tanvi3004/AgriAI-CropAdvisor
```
4. Run the Notebook:
Execute each cell in sequential order by selecting the cell and pressing Shift + Enter.
You can modify the input data (e.g., soil and climate parameters) in the designated cell to test predictions for various conditions.
View data visualizations, cluster analysis, and prediction results directly in the notebook.

## Key Features :
- Visualization: Graphs for distribution of soil nutrients, temperature, humidity, pH, and rainfall.
- Clustering: Crop grouping based on shared requirements.
- Prediction: Suggests the optimal crop for custom soil and climatic inputs.

## Result :
- The system groups crops into 4 distinct clusters based on environmental similarities.
- Predictive accuracy is evaluated with metrics like precision, recall, and F1-score.
- Example Predictions:
  - For input [90, 40, 40, 20, 80, 7, 200]: Suggested crop is Rice.
  - For input [20, 30, 10, 15, 90, 7.5, 100]: Suggested crop is Wheat.
    
## Conclusion :
- This project demonstrates how machine learning can assist in sustainable agriculture by:
  - Identifying optimal crops for specific conditions.
  - Enhancing resource utilization.
  - Supporting data-driven decision-making in farming practices.

