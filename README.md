# Software platform recomendation based on data

## Installations

The code is written in Python.
You need some basic libraries:
- Numpy
- Pandas
- Matplotlib
- IPython
- Collections

You need to download the suvey files from stack overflow.
The survey data is available at https://insights.stackoverflow.com/survey

Here you have the link to the files we need:
https://info.stackoverflowsolutions.com/rs/719-EMH-566/images/stack-overflow-developer-survey-2022.zip

Extract please the following two files from the zip and put them into the code root directory:
**survey_results_public.csv**
**survey_results_schema.csv**

## Project Motivation

With this project, it is possible to load the survey data and analyse the aspects related to a software enviroment.

For this purpose you can find an easy program structure to load, clear and analyse the data for this purpose.

## File Descriptions

The code is at the followind notebook file:
**SW_recomentation_based_on_data.ipynb**

In oder to run it, you need the two .csv files mentioned before.

## How to Interact with your project

In the code there is the posibility to generate a dictionary witch is important for the data analysis. If you activate it, it generates following file:
**column_element_set_dictionary.npy**
The idea is that you don´t need to generate the dictionary every time, because it is time consuming. Instead you can choose to load the dictionary from this file. It is much faster!


## Licensing, Authors, Acknowledgements

Please feel free to use my code.

Thanks for Stack Overflow for doing this survey every year and provide the results public, so each one can look for answers based on data ;-)



