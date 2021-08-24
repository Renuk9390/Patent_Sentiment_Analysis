# Dataset for annotation 

## Files and their description

1.	combined_all_stats_csv 
	- This is the CSV File containing statstics for patent dataset  
		> can be download from the Git Repo.
	- What are the statatistics it shows ?	
		> This file contains columns such as filename, total publications, total positive samples, total negative samples, and total neutral samples per every week of the year from 2010-2020. 

2. combined_neut_data_csv 
	- This is the CSV File, that contains details regarding neutral samples 
		> Can be downloaded from [here](https://drive.google.com/file/d/1-YCku0qx74cmbSm7R_7t7C6K9jdmvTn1/view?usp=sharing)  	
	- What data this file contains?
		> This file contains columns such as publication_number, patent_title, appl_type, and neutral_text for each patents.	

3. combined_pos_data_csv 
	- This is the CSV File, that contains details regarding positive samples 
		> Can be downloaded from [here](https://drive.google.com/file/d/1-I_HVrIVVZ0hFPk32GcqTpUXdk-4Nr2l/view?usp=sharing).  	
	- What data this file contains?
		> This file contains columns such as publication_number, patent_title, appl_type, and positive_text for each patent.	 

4. combined_neg_data_csv 
	- This is the CSV File, that contains details regarding negative samples 
		> Can be downloaded from [here](https://drive.google.com/file/d/1-PDCkcrrDCtFnKy5MJFuaKJ0T8A4r1_S/view?usp=sharing)  	
	- What data this file contains?
		> This file contains columns such as publication_number, patent_title, appl_type, and negative_text for each patent.	 

5. combined_data_150k
	- This is the CSV File, that contains 150k cleaned data samples(50k from each pos, neg, and neut) required to train models. 
		> Can be downloaded from [here](https://drive.google.com/file/d/1nMdnmJ3_JdcgNFB8C9O8URUWEqFYg01m/view?usp=sharing)  	
	- What data this file contains?
		> This file contains two columns text and target. 
		> Text can be neutral, positive, or negative.  
		> Target can be label 0, 1, 2 for neutral, positive, and negative respectively.    