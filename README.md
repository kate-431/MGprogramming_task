## Mantel Group technical assessment


The aim of the following task is to create a dataset from a collection of JSON files which contain hourly weather data for a number of cities in Australia over a period of 24 hours. The Weather_task.ipynb code in this respitory complete the following tasks:

1. Reads the data contained within the JSON files and creates a Pandas dataframe.
2. Transforms and loads the data to produce the following two outputs containing:
a. The average temperature for each city.
b. The top three most common “weather text” for each city.
3. Save the two results you produce in CSV format.

## Requirements

This project is coded in a Google Colab Juypter notebook which uses Python 3.6, and so this guide assumes you are using the same. The project's dependencies are listed below:
* numpy
* pandas
* json
* google.colab
* glob
* os
* collections

## Running the program

As the programs were created in google colab, the following instructions explain how to run this program in colab, it can also be run on a local Juypter Notebook.
Clone the github respitory to your google drive using the code below.

!git clone https://github.com/kate-431/MGprogramming_task

The files are now saved on your google drive ready to be used, go to https://drive.google.com/drive/my-drive and a new folder MGprogramming_task should be present with the program in it. 

Open the program Weather_task.ipynb,  the JSON files will need to be present in your google drive and the code will required to be edited for the link to the folder which contains the JSON files or an alternative is upload the files. Once complete, click run all. The program should run and two CSV output files will download onto your local computer containing the information required.


