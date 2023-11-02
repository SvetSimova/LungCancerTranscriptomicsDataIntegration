This is my part of work in Bioinformatics project 
"Lung Cancer Transcriptomics Data Integration"
in which I solved the following problems as Data Scientist:
Data Preparation, Feature Selection, PCA, Classification.

It consists of:
 1. Data_Description.txt file with data description;
 2. four Jupyter Notebook files:
	-- L_Data_Preparation.ipynb, where 
		all original data from 4 csv files is combined in one DataFrame, 
		distributions for GTEx and TCGA datasets were compared and normalized
		(Questions 1.1, 1.2, 1.4 from Data_Description.txt)
	-- L_PCA_State.ipynb with appliance of Principal Component Analysis
		(Question 1.3 from Data_Description.txt)
	-- L_Feature_Selection_State.ipynb where 
		the best predictors for 3 class classification were chosen
		(Question 2.1 from Data_Description.txt) 
	-- L_Modelling_State.ipynb with investigation of classification models
		(Question 2.2 from Data_Description.txt)
 3. My_Pred_Modelling.py file with additional functions that are used in several .ipynb files.
 4. the last file is the Workflow_Review.docx with the intermediate results 
	and the description of the whole workflow.

I realize that this is not the best version of the solution, 
but it is a fairly fast and quite acceptable implementation of the assigned tasks.
