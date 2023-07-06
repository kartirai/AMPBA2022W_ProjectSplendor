# AMPBA2022W_ProjectSplendor
Capstone project for the ISB AMPBA Course 2022 Winter batch

# Execution of Files
1. Streamlit Application: 
	1.	Make sure you have the necessary libraries installed, including streamlit and PyGitHub. You can install them using requirement.txt file 
	2.	Open a terminal or command prompt and navigate to the directory where the file is saved.
	3.	Run the Streamlit app by executing the command streamlit run main.py.
	4.	The Streamlit app will start running, and you will see a URL (e.g., http://localhost:8501) in the terminal.
	5.	Open a web browser and enter the URL from the previous step.
	6.	The Streamlit app will be displayed in the browser, and you can interact with it, including uploading a file and seeing the file uploaded to the specified GitHub repository.

2. EDA file,Customer Insights,Model files - use jupyter notebook to execute the notebook, make sure all libraries are pre installed and the file URL is correct. We have provided the input file as well feel free to read it from your local system. We have provided the json keys as well, feel free to read them in the code as per your comfort (from your local system). Incase if the key fails then we have exhausted the number of times we can extract results from them for free.
   
# Project Splendor - Machine Learning Project

![Project Splendor](https://github.com/kartirai/AMPBA2022W_ProjectSplendor/raw/master/images/splendor_logo.png)

## Table of Contents

- [About](#about)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Exporting Predicted Values](#exporting-predicted-values)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About

Project Splendor is a machine learning project that focuses on the implementation of logistic regression models. The project contains two code files: one with a logistic regression model using traditional methods and another with a logistic regression model based on the Keras library. Additionally, it features a streamlined application that enables users to upload a dataset file, execute the models, and predict values. Exploratory data analysis (EDA) has been conducted on the dataset, and the project includes the code file for the analysis. The predicted values from the model execution can be exported to word cloud platforms, BigQuery, and Google Sheets.

## Installation

To use this project, follow these installation steps:

1. Clone the repository:

```bash
git clone https://github.com/kartirai/AMPBA2022W_ProjectSplendor.git
```

2. Navigate to the project directory:

```bash
cd AMPBA2022W_ProjectSplendor
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

To use the streamlined application and execute the logistic regression models, follow these steps:

1. Launch the application:

```bash
python app.py
```

2. Upload the dataset file through the application.
3. Perform model execution and obtain predicted values.

## Exploratory Data Analysis

The project includes a dedicated file, `eda.ipynb`, for conducting exploratory data analysis (EDA) on the dataset. This file contains detailed analysis, visualizations, and statistics to gain insights into the dataset.

## Exporting Predicted Values

After completing the model execution and obtaining the predicted values, the project offers functionality to export these values to various platforms, including:

- Word cloud platforms
- BigQuery
- Google Sheets

Please refer to the respective code files within the repository for specific instructions on exporting the predicted values to each platform.

## Contributing

Contributions to this project are welcome. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your modifications.
4. Commit your changes and push your branch to the remote repository.
5. Submit a pull request describing your changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or suggestions, please contact [your-email-address].
