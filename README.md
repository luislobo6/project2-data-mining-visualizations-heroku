# project2-data-mining-visualizations-heroku
Project for Data Mining Visualizations cleaned to upload to Heroku

Welcome to the Mexico Mining Visualizations Dashboard
With the files in this repository you can request, save and visualize the Mexico mining information from the latest national survey.
Please follow the next file running sequence to ensure a correct flow of information:
API_request.ipynb - This is a jupyter notebook file that is intended to run a request to INEGI´s API asking for the complete information of over 200
		data codes that contains the mining output per localization.
app.py - Use your python version to run this flask application.

Do not! run file MexicoMaps.ipynb, this file creates a geojson file that will take several minutes to run, since the information processed
in this file is very large. We provide the output of this code on "/static/data/mexico_ent.geojson"


