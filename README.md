Intellihack_TeamX_Task1
Weather Forecasting for Smart Agriculture
Overview
This project predicts daily rain occurrence using historical weather data (over 300 days) to generate a 21-day rain probability forecast. The system is designed to help farmers plan their irrigation, planting, and harvesting schedules more effectively by providing accurate, hyper-local weather predictions.

Key Features
Data Preprocessing:
Handles missing values, converts dates to datetime, and extracts additional features (month, day, weekday).
Exploratory Data Analysis (EDA):
Visualizes distributions of weather features and examines correlations with the target variable.
Model Training & Evaluation:
Uses logistic regression as a baseline model with hyperparameter tuning to predict rain occurrence.
Future Predictions:
Generates rain probability forecasts for the next 21 days.
Reproducibility:
Provides clear instructions for setting up and running the project.
Project Structure
bash
Copy
Intellihack_TeamX_Task1/
├── src/                # Source code files (Python scripts, notebooks, etc.)
├── docs/               # Documentation (LaTeX, PDFs, etc.)
├── weather_data.csv    # Dataset file
├── README.md           # Project overview and instructions (this file)
└── .gitignore          # Specifies files and folders to be ignored by Git
Running Instructions
Pre-requisites
Python Environment: Python 3.7 or later.
Required Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, tabulate.
Installation:
bash
Copy
pip install pandas numpy matplotlib seaborn scikit-learn tabulate
Steps to Run the Project
Download the Dataset:
Place the file weather_data.csv in the root directory of this repository.
Clone the Repository:
bash
Copy
git clone <your-repository-URL>
cd Intellihack_TeamX_Task1
Run the Jupyter Notebook or Python Scripts:
The project is structured into several sections:
Data Loading and Preprocessing
Exploratory Data Analysis (EDA)
Model Training and Evaluation
Hyperparameter Tuning
Future Predictions
Execute the cells in the provided Jupyter Notebook sequentially or run the Python scripts as instructed.
Review the Outputs:
Check the console output for evaluation metrics (accuracy, precision, recall, F1-score, ROC-AUC) and verify the 21-day rain probability predictions.
Modify as Needed:
To experiment with different scenarios or extend the prediction horizon, adjust parameters in the Future Data section.
Team Members
Team Leader: [Your Name]
Collaborators: [Team Member 1], [Team Member 2], [Team Member 3], ...
License
This project is licensed under the MIT License.

Acknowledgements
This project is part of the Intellihack competition. Please adhere to all submission guidelines as outlined in the task instructions.