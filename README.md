# NER_Discharge_Note

Chart reviews are a commonplace procedure to maintain quality, compliance, ethics, and consistency of patient medical records. While lots of information can be extracted from structured fields, free-text notes, written by the clinician, can offer invaluable new, unique, or additional insights. 

In this case, Natural Language Processing models, pre-trained for clinical text analysis, have been applied to identify and extract drug names, with their corresponding dose/route/frequency from a discharge note. This pipeline can be used for
1. Extracting the target combination: drug/dose/route/frequency to review the clinician’s prescription practices. 
2. Comparing the drug record from discharge notes to the one from the Medications section of the chart for quality and compliance.  
3. Re-purposing the pattern to extract other target entities from the notes such as complaints, tests, diseases. 

The Python code (Google Colab friendly) is provided. Please note that due to the rules on using the MIMIC-III data set, the data are not provided. However, the code can be applied to any discharge text. Please refer to the Requirements.txt file to review the required libraries and models. 

I recommend reviewing the accompanying short slide deck for the detailed project description and results. 
