# Loan-Prediction-with-ML
It was a final project during my Data Scientist course. I gained 370/380 points.

Dataset is in zipfile



Lending Club is a peer-to-peer lending company that connects borrowers with investors through an online platform. It serves people who need personal loans ranging from $ 1,000 to $ 40,000. The borrowers receive the full amount of the loan granted, minus the initial fee, which is paid to the company. Investors buy promissory notes backed by personal loans and pay the Lending Club a service fee. The Lending Club company provides data on all loans granted through its platform during certain periods.
For the purposes of this project, data on loans granted through the Lending Club in the years 2007-2011 were used. Each loan has an indication of whether it has finally been repaid (Fully Paid or Charged off in the loan_status column). Your task is to build a classification model that, based on this data, will predict with a certain accuracy whether the potential borrower will repay his debt on the loan taken. The data set is accompanied by a file with a description of all variables and a file "FICO Score ranged.pdf", in which the meaning of one of the columns is described in detail.

Below are presented the individual stages of the analysis, the execution of which is necessary to complete the project, and their scoring:
1) Data Processing- as an experienced Data Scientist, you probably know the individual steps that must be performed at this stage, so we will not list them here.
    EDA, i.e. extensive data mining (100 points). Describe the conclusions of each graph, support your hypotheses with statistical tests such as t-test or Chi-square. Additionally, answer the following questions:
        How does the FICO score relate to the borrower's probability of repaying a loan?
        How is the credit age related to the probability of default and is this risk independent or related to the FICO score
        How is my home mortgage status related to my likelihood of default?
        How is annual income related to the probability of default?
        How is your employment history related to the probability of default?
        How is the size of the requested loan related to the probability of default?
 2) Feature Engineering - Create 20 new variables
 3) Modeling
        Perform data clustering (try several methods for this purpose, at least 3) and check if there are any borrower segments, use appropriate methods to determine the optimal number of clusters
        Train 5 different models, using a different algorithm for each one, and then compare their operation, take the AUROC score as the model quality assessment metric.
        Check the operation of the previously used methods on compressed data using PCA, compare the results (AUROC score) with the models trained in the previous section.
        Build the final model, the AUROC score of which will be> = 80%, remember to select important variables, cross-validation and fine-tune the model parameters, also think about class balancing.
        
        
        
