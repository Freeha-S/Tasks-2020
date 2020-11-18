# Tasks-2020
## Machine Learning and Statistics Assessment Tasks 2020

My submission for the Tasks 2020 assessment for Machine Learning and Statistics module at GMIT.

## Lecturer
Dr. Ian McLoughlin

## About this Repository
This repository contains jupyter notebook called task-2020.ipynb which contains four tasks completed as part of Assessment. these tasks are
1. Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. Your code should not depend on any module from the standard library1 or otherwise. You should research the task first and include references and a description of your algorithm.
2. The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table below as an example [4], stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value. You should include a short note with references justifying your analysis in a markdown cell.
3. The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)) .However, Microsoft Excel has two different versions of the standard deviation calculation, STDDEV.P and STDDEV.S . The STDDEV.P function performs the above calculation but in the STDDEV.S calculation the division is by len(x)-1 rather
than len(x) . Research these Excel functions, writing a note in a Markdown cell about the difference between them. Then use numpy to perform a simulation demonstrating that the STDDEV.S calculation is a better estimate for the standard deviation of a population when performed on a sample. Note that part of this task is to figure out the terminology in the previous sentence.

## How to clone this repository
- Go to GitHub.
- Go to  repository: https://github.com/Freeha-S/Tasks-2020
- Click the Code button.
- Click on HTTPS and copy the link that is shown.
- Open the command line on your machine, navigate to the directory where you would like to clone the repository down to.
- Enter the command: git clone followed by the URL of the repository.
- The repository will be cloned down to your current working directory.

## How to view & run the jupyter notebook
- On the command line navigate to the folder location where the repository has been downloaded and saved to using the cd change directory command.
- Type jupyter notebook on the command line and press enter
- jupyter notebook will open in your web browser.
- Open the task-2020.ipynb notebook in the browser and the notebook containing the code and comments will be displayed.
- To run the entire notebook click Kernel in the toolbar at the top of the screen and then click Resstart and run all. The notebook will refresh and all code cells will be executed from top to bottom.
- if you want to run the code in any specific cell hold down the shift key and press enter and the command will run and the output wil be displayed in the next cell.
- To change between edit and read mode at any time press the ESC key.

after viewing the jupyter notebook close the web browser and return to the command line. Press Ctrl + C on the command line to stop jupyter notebook.
## Problem in veiwing jupyter notebook on Github
if jupyter notebook does not load on Github website. you can copy and paste the URL of the notebook and paste in the following website https://nbviewer.jupyter.org/ which will display the notebook: 
URL for jupyter notebook : https://github.com/Freeha-S/Tasks-2020/blob/main/task-2020.ipynb

 
