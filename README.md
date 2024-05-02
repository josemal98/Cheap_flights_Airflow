# Search of cheap flights with Airflow

This repository is part of a project of the Data Engineering course of the Master's Degree in Data Science of the Universidad de Sonora. In general terms, the project consists of developing and implementing a data pipeline on the Airflow platform. More specifically, I decided that the goal of my project is to automate the search for cheap flights. For this I developed a Dag in Airflow that as a first step extracts information about available flights from a predetermined origin and to a predetermined destination. This first step is performed by means of a request to the free API: [Travelpayouts Data API](https://travelpayouts-data-api.readthedocs.io/en/latest/).
