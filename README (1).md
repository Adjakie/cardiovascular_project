{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "0d9d976a-38c4-49d4-a037-ca46bef57d44",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "# Cardiovascular Disease Prediction Project\n",
    "\n",
    "## Project Overview\n",
    "This project analyzes cardiovascular disease data to predict health risks using machine learning models. The dataset includes patient health indicators such as blood pressure, cholesterol levels, and lifestyle factors.\n",
    "\n",
    "## Tools Used\n",
    "- **Python** (Data processing, modeling)\n",
    "- **Pandas, NumPy** (Data manipulation)\n",
    "- **Matplotlib, Seaborn** (Data visualization)\n",
    "- **Scikit-learn** (Machine learning models)\n",
    "\n",
    "## Key Steps\n",
    "1. **Data Cleaning & Preprocessing**\n",
    "   - Handled missing values and outliers\n",
    "   - Normalized numerical features\n",
    "2. **Exploratory Data Analysis (EDA)**\n",
    "   - Visualized distributions with histograms and box plots\n",
    "   - Examined correlations between features\n",
    "3. **Model Training & Evaluation**\n",
    "   - Trained **Logistic Regression** and **Random Forest** models\n",
    "   - Evaluated performance using accuracy and classification reports\n",
    "   - Achieved ~71% accuracy\n",
    "\n",
    "## Results\n",
    "- Logistic Regression: **71.3% Accuracy**\n",
    "- Random Forest: **71.3% Accuracy**\n",
    "\n",
    "## Repository Structure\n",
    "```\n",
    "📂 Cardiovascular-Analysis-Project  \n",
    "│── 📄 cardiovascular_analysis.ipynb  (Code with comments)  \n",
    "│── 📄 cardio_data.csv  (Dataset)  \n",
    "│── 📄 README.md  (Project description)  \n",
    "│── 📄 requirements.txt  (Dependencies)  \n",
    "│── 📂 results/  \n",
    "│      ├── model_accuracy.png  \n",
    "│      ├── feature_importance.png  \n",
    "```\n",
    "\n",
    "## How to Use\n",
    "1. Clone the repository:\n",
    "   ```bash\n",
    "   git clone https://github.com/YOUR_GITHUB_USERNAME/Cardiovascular-Analysis-Project.git\n",
    "   ```\n",
    "2. Install dependencies:\n",
    "   ```bash\n",
    "   pip install -r requirements.txt\n",
    "   ```\n",
    "3. Run the Jupyter Notebook to analyze the data and train models.\n",
    "\n",
    "## Future Improvements\n",
    "- Experiment with other models like **XGBoost**\n",
    "- Tune hyperparameters for better performance\n",
    "- Deploy as a web app for predictions\n",
    "\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "7e487e42-27c4-4a17-908f-ba2e61ddac90",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.12.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
