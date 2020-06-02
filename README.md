### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)

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

Here in Ecuador, there are plenty of training centers that deliver not only presencial but also online courses of any kind, but most of them aren't related to the actual job requirements, so the idea of this project is to map the training courses offer with the job required in the local market. 

**Note, the comments and findings in the notebook are in Spanish due to the information gathered is in Sapnish as well**

There are three main csv files, which include: 

* `jobs_csv_limpio.csv`, including information gathered from some job offers platforms.
* `training_center_ec.csv`, including information about the courses offered by a training center.
* `training_center.R`, including the cleaning and feature engineering of the training center information.

## File Descriptions <a name="files"></a>

The cleaning and feature engineering done in the training center file was developed in R language program, but there is one main notebook developed in Python used to analyze the information of the both csv files mentioned above. Basically, an EDA was developed to map courses offered from the training center with the job offers. Furthermore, Markdown cells support and clarify the process done in the EDA.

## Results<a name="results"></a>

The results are split in two: 
* Findings related to the jobs offer file, including that there are more requirements for non-tech jobs thant for the tech ones; next, the majority of the jobs are concentrated in three main `Provicias` such as Guayas, Pichincha and Azuay, and finally, the top three jobs offer are `Desarrollador Web`, `QA tester` and `Community Manager`. On the other hand, the top non-tech jobs are `Asistente`, `Vendedor` and `Ejecutivo`.

* Findings in training center file, including the top three courses are `Emprendimiento`, `Metodologias_Agiles_Lean`, and `Marketing_digital` which aren't related with not only the jobs offer but also the skill required. Second, the courses were taken mostly from people of the following Provincias `Pichincha`, `El Oro` and `Guayas`, so we can see that two Provincias out of three are the same from the previous analysis. Finally, there is not only relation between courses offered by the training center and the jobs offer, but also the skills required don't match neither, so training centers should consider the real and the actual requirements of the local market in Ecuador and deliver courses focused on jobs and skills needed to to the job.

