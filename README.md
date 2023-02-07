# Overview
This project was developed with python, where I ingested open data from the country of Colombia, obtaining the file of fuel prices in the country, where I have carried out the processes of Extraction, Transformation and Loading of the data.
It was deployed in Streamlit.io to create a data visualization and do it as a web application.

# Project Contents
The project contains the following files and folders:
* app.py: main file that will be executed to deploy the application in streamlit.io
* cred_here: is the file where it will contain the API key provided by streamlit.io
* requeriments: the necessary libraries to be able to execute the project correctly
* Dockerfile: It is used to be able to deploy the project to any PC without problems through Docker
* utils.py: the file where some transformations and functions are performed

# Deploy The Project
In order to deploy the project correctly it is necessary to register to Streamlit.io, modify the cred_here.py file and execute "stream run app.py" so that it can be executed on the aforementioned website.
