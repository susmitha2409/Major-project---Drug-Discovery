Drug Combination Prediction using Machine Learning with Gene Information Integration
This project focuses on developing a machine learning model to predict optimal drug combinations by incorporating gene information. The primary aim is to identify strain-specific drug combinations, moving beyond species-specific predictions.

Key Features
Machine Learning Models:

Implemented five different machine learning models for the classification task.
Selected the best-performing model based on performance metrics.
Fingerprint Selection:

Evaluated three types of molecular fingerprints: ECFP, Morgan, and MCC key.
Chose the most effective fingerprint for the final classification.
User-Friendly Interface:

Developed a Streamlit interface where users can input drug names and retrieve the most suitable drug combinations.
Data Visualization:

Created a Power BI dashboard to visualize and analyze the dataset, enhancing the interpretability of results.
Project Structure
code/: Contains the Python scripts used for model training, evaluation, and the Streamlit interface.
data/: Includes the datasets used in the project.
dashboard/: Power BI files and related resources.
notebooks/: Jupyter notebooks used during the research and development phase.
README.md: This file, providing an overview of the project.
Installation

Install the required Python packages:
bash
Copy code
pip install -r requirements.txt
Usage
Run the Streamlit interface:

bash
Copy code
streamlit run app.py
Enter the drug name in the interface to find the optimal combination.
Power BI Dashboard:

Open the provided .pbix file in Power BI to explore the data visualizations.
Contributing
Feel free to fork the repository and make improvements. Pull requests are welcome!


Acknowledgments
Special thanks to SASTRA University for their support.
