# Software Developer Salary Estimator Tool

This project is a tool for estimating the salary of software developers based on their country of residence, level of education, and years of experience. It uses data from the [Stack Overflow Survey 2020](https://insights.stackoverflow.com/survey/2020) to make predictions and provides users with an easy-to-use GUI developed with Python and Streamlit.

## How to use the tool

To use the tool, simply go to the [Streamlit app link](https://vrajeshbrahmbhatt06-developer-salary-prediction-tool-app-e7wppf.streamlit.app/) and select the "Predict" tab. Then, select your country of residence, level of education, and years of experience using the dropdown menus. The tool will then estimate your salary based on your inputs.

In addition, the "Explore" tab provides some visualizations based on the Stack Overflow Survey 2020. Users can view the number of respondents from different countries, the average salary based on country, and the average salary based on years of experience.

## Tool Screenshots and Visualizations

Here are some screenshots of the tool in action:

<img src="https://i.ibb.co/5TJJTsR/tool1.png" alt="App Screenshot" width="500" height="400">

And here are some visualizations from the "Explore" tab:

<img src="https://i.ibb.co/8xswxFm/vis1.png" alt="App Screenshot" width="500" height="400">
<img src="https://i.ibb.co/dWN5DKv/vis2.png" alt="App Screenshot" width="500" height="300">
<img src="https://i.ibb.co/cgGsyTz/vis3.png" alt="App Screenshot" width="500" height="300">


## How to run the project locally

To run the project locally, follow these steps:

1. Clone the repository to your local machine.
2. Install the required packages listed in `requirements.txt` using the following command: `pip install -r requirements.txt`
3. Run the `app.py` file using the following command: `streamlit run app.py`.
4. Open a web browser and go to `localhost:8501` to access the tool.

## About the dataset

The dataset used in this project is the [Stack Overflow Survey 2020](https://insights.stackoverflow.com/survey/2020). It contains responses from thousands of software developers from around the world and provides valuable insights into the demographics and working conditions of the software development industry.

## Requirements

- numpy==1.24.3
- pandas==1.5.3
- matplotlib==3.7.1
- scikit-learn===1.2.2
- streamlit===1.21.0


## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](https://github.com/Vrajeshbrahmbhatt06/Developer-Salary-Prediction-Tool/blob/d9fc723b74b185a291890991a5f677c4ccf29dba/LICENSE) file for more information.
