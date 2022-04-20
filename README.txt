File to be run on Jupyter Notebook (Python 3)

(Can be installed via Anaconda / https://jupyter.org/install) 

Ensure internet connectivity before running the code. 
Data bases needed to be stored in the same file as that of code. 

Dataset specification to ensure before running the project file (given or other):
1. 'Days' should be formatted general. 
2. Rest of the coloumn heading must be formatted as time(hh:mm:ss). 
3. All the rows with dates must be formatted as date (yyyy-mm-dd)
4. Reformatting maybe required every time before running the code after new data is added.

(Incase of sample dataset file 'DATASETAI' giving type errors values refer 
to above specifications or original dataset can be copied from file 'DATA' as backup) 

Libraries required:

pandas -> storing and manipulating data set
numpy -> manipulating data set
matplotlib -> to show graphs  
statsmodels.tsa.ar_model -> for running Auto regression function
math -> calucation of error
datetime -> adding new data and predictions


Process: 
Run project code in modules order as given in the file. 
Part of planning and view requires previous prediction parts to be run.  
Ensure database excel file is closed before and while running the code for smooth updating.  