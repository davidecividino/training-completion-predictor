# HR Analytics challenge
A colleague from the Learning Team, who is responsible for digital trainings, has approached you and would like your help in understanding the completion rates for their online trainings. They would also like you to build a model that estimates the probability that an employee completes a training.
To this end, they have provided you two data files: “employee.csv” and “performance.csv”. The first file (“employee.csv”) contains HR data regarding our employees, while the second file (“performance.csv”) contains information about an employee’s performance rating from our performance management system.
Using these two files (containing synthetic data) and either R or Python:
Undertake the necessary steps to
1. Build a model that estimates the probability that an employee completes a training
2. Write a short summary (bullet points and comments in your code/notebook/markdown are perfectly fine) that gives your colleague some insights into the top 5 drivers of your estimates as well as an evaluation of the model’s performance. Since we do not have provided a detailed codebook, feel free to provide your own interpretation as to what these variables might mean (don’t worry, there are no wrong answers).

# Repository structure
Two main files containing the analysis:
* Exploratory_Data_Analysis.Rmd: file generating the Exploratory Data Analysis and containing the information on the task details (start from here)
    The Rmd script generates the html file Exploratory_Data_Analysis.html
* model_constuction.ipynb: Jupyter Notebook containg the model definition, performance evaluation and discussion of results and insights in Jupyter Notebook.
    The Jupyter Notebook generates the html file model_constuction.html

One folder with all the data data/, stuctured into two subfolders:
* raw/: with the two raw datasets
* clean/: with the final cleaned dataset

Please start from Exploratory_Data_Analysis.Rmd (Exploratory_Data_Analysis.html) and then move to model_constuction.ipynb (model_constuction.html).
