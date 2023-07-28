=======

# How to read my files

Video presentation:
https://share.vidyard.com/watch/6nDn7TjG4SLiorbCg4Pmfo?

For EDA, please open:
  - EDA_and_Streamlit/get_around_EDA.ipynb for the whole code
  - EDA_and_Streamlit/app.py for the streamlit file code
  - https://getaround-streamlit-elo-59c51a01702a.herokuapp.com/ for the hosted version

For Machine Learning model, please open:
  - Machine_Learning/get_around_model_quali.ipynb for the whole code

For the API, please open:
  - API/app.py for the code
  - https://getaround-api-elo-f1df83a28de6.herokuapp.com/docs for the hosted API

=======


# GetAround Case Study

GetAround is the Airbnb for cars, allowing users to rent cars from individuals for short periods. As a partner of Jedha, GetAround has presented a challenge related to optimizing the rental process and pricing.

## Project Overview

The project involves analyzing data from GetAround to address specific challenges and provide insights. The main objectives are:

1. Implementing a minimum delay between rentals to reduce late returns and improve customer satisfaction.
2. Analyzing the impact of the minimum delay on owner revenues and the number of affected rentals.
3. Examining the frequency of late check-ins and their impact on subsequent rentals.
4. Assessing the number of problematic cases the minimum delay would solve based on different thresholds and scopes.

Additionally, the Data Science team is working on pricing optimization and requires an API endpoint to provide car price predictions.

## Dashboard

A web dashboard is developed to assist the Product Management team in addressing the challenges mentioned above. Streamlit or any other suitable technology can be used to create the dashboard.

## Machine Learning - /predict Endpoint

In addition to the dashboard, a machine learning model is built to optimize car prices for GetAround's owners. The model provides predicted prices through an API endpoint. The endpoint follows this format: `https://your-url.com/predict`.

- Endpoint: `/predict`
- Method: POST
- Input: JSON data
- Output: JSON response with a `prediction` key

Example input:
{
  "input": [[7.0, 0.27, 0.36, 20.7, 0.045, 45.0, 170.0, 1.001, 3.0, 0.45, 8.8]]
}

Example output:
{
"prediction": [6]
}


## Documentation Page

A documentation page is provided for the API, accessible at `/docs` of the hosted website (e.g., `https://your-url.com/docs`). The documentation includes:

- Title: A descriptive title.
- Endpoint Descriptions: Details of each available endpoint, including the endpoint name, HTTP method, required input, and expected output.

Styling and additional relevant information can be included in the documentation.

## Online Production

The API and dashboard should be hosted online to facilitate access and evaluation. Heroku is recommended as a hosting provider, but any other provider can be used.

## Helpers

To aid in the project, the following tips are provided:

- Spend time understanding the data.
- Pay attention to data analysis, as valuable insights can be derived.
- Allocate 2 to 5 hours for data analysis and 3 to 6 hours for machine learning tasks.
- Consider using libraries like MLflow to manage the machine learning workflow.

## Deliverables

To complete the project, the following deliverables are expected:

- A production-ready dashboard accessible via a web page.
- The entire code stored in a GitHub repository, with the repository URL provided.
- A documented online API hosted on Heroku (or another chosen provider) that includes at least one `/predict` endpoint. The API should follow the technical description provided.

To evaluate the project, ensure the code is shared in a GitHub repository with a README.md file that includes a brief project description, instructions for local setup, and the online URL for the deployed project.

## Data

Two data files are provided for the project:

1. Delay Analysis: Contains data for data analysis tasks.
2. Pricing Optimization: Contains data for machine learning tasks.

Happy coding! 👩‍💻
>>>>>>> b73fb29d4c9bf81fa87bc91635f378ab1d9a25dd
