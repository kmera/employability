### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The libaries needed to run the code, using Python version 3.* are:

* Pandas
* NumPy
* Matplotlib

And the libraries for R file using R version 4.* are:

* readxl
* dplyr
* tidyr
* ggplot2
* Amelia
* stringr

## Project Motivation<a name="motivation"></a>

Here in Ecuador, there are plenty of training centers that deliver not only presencial but also online courses of any kind, but most of them aren't related to the actual job requirements, so the idea is to map the training courses offer with the job required in the local market. **Mostly, the comments and findings in the notebook are in Spanish**

There are two main csv files, which include: 

* `jobs_csv_limpio.csv`, including information gathered from some job offers platforms.
* `training_center_ec.csv`, including information about the courses offered by a training center.
* `training_center.R`, including the cleaning and feature engineering of the training center information.

## File Descriptions <a name="files"></a>

There is one main notebook used to analyze the information of the both csv files. Basically, an EDA was developed to map courses offered from the training center with the job offers. Furthermore, Markdown cells support and clarify the process done in the EDA.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@klever.mera/thinking-to-travel-to-boston-after-the-lockdown-f84a99ec728e).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Boston Airbnb Open Data in Kaggle for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/airbnb/boston).  Otherwise, feel free to use the code here as you would like! 

