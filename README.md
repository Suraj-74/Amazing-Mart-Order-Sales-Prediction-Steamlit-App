# Amazing Mart Order Sales Prediction - Streamlit App
Welcome to the Github repository for the Order Sales Prediction Streamlit App. This Project aims to provide a user friendly web application that predicts the sales of an amazing mart order based on a various parameter. The app is built using streamlit, a most popular python library for creating interactive web appllication.
## Features
1. Explore the dataset and visualize the data.
2. Predict the sales of an orders based on its features.
3. Input various order parameters, such as Days to Ship, Ship Mode, Place, Segment, Region, Categories, Sub-Categories, Discount, Actual Discount, Quantity, to get an estimated sales.
4. The app uses a best trained machine learning model to make predictions.
## Model Deployment
We are pleased to announce that the project has been successfully deployed using Streamlit. You can access the live deployment of the Order Sales Prediction model by following this link:[Order Sales prediction Deployment](https://skill-academy-internship-gadtvndyqmznjegkukcnm3.streamlit.app/)
## Usage 
Once you access the Streamlit app, you will be able to interact with the model's user-friendly interface. Simply input the relevant features of the car you want to predict the sales for, and the model will provide you with an estimated sales based on the trained data. Feel free to experiment with different combinations of features and explore the model's performance.
## Feedback and Contributions
Your feedback and contributions are highly appreciated. If you encounter any issues, have suggestions for improvement, or would like to contribute to the project, please don't hesitate to create an issue or submit a pull request in this repository.
## Project Structure
The repository has the following structure:

Order-Sales-prediction-streamlit/ ├── app.py ├── merged_data.csv ├── bst_model.pkl ├── README.md └── requirements.txt

1. `app.py`: The main Python script that contains the Streamlit app code.
2. `merged_data.csv`: It has the Dataset of Amazing mart order sales.
3. `car_predict/`: It has saved the best model to trained the data.
4. `README.md`: This readme file.
5. `requirements.txt`: List of Python packages required to run the app.
## Model Training
The machine learning model used in the app is trained separately and saved as a serialized file (`bst_model.pkl`). If you want to train your own model, you can refer to the Jupyter Notebook provided in the repository.
## Contribution
Contributions to this project are welcome! If you find any issues or have suggestions for improvements in my code, please open an issue or submit a pull request. Let's make this project even better together.
## Acknowledgements
We would like to express our gratitude to those resources for their valuable contributions:
