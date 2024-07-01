# Dataset for annotation 

## Files and their description

1.	combined_all_stats_csv 
	- This is the CSV File containing statstics for patent dataset  
		> can be download from the Git Repo.
	- What are the statatistics it shows ?	
		> This file contains columns such as filename, total publications, total positive samples, total negative samples, and total neutral samples per every week of the year from 2010-2020. 

2. neutral_data
	- This is the CSV File, that contains details regarding neutral samples 
		> Can be downloaded from [here](https://drive.google.com/file/d/1YV6vLXIDnhuHYLps79cQB5JZLHybQKGu/view?usp=sharing)  	
	- What data this file contains?
		> This file contains columns such as publication_number, patent_title, appl_type, and neutral_text for each patents.	

3. positive_data 
	- This is the CSV File, that contains details regarding positive samples 
		> Can be downloaded from [here](https://drive.google.com/file/d/17omak-R3Q7aQnbNOBT7nXCAPERT3sa4m/view?usp=sharing).  	
	- What data this file contains?
		> This file contains columns such as publication_number, patent_title, appl_type, and positive_text for each patent.	 

4. negative_data
	- This is the CSV File, that contains details regarding negative samples 
		> Can be downloaded from [here](https://drive.google.com/file/d/1QL5eCP0E405rlfjxw2G8hAFxInlg9CWw/view?usp=sharing)  	
	- What data this file contains?
		> This file contains columns such as publication_number, patent_title, appl_type, and negative_text for each patent.	 

5. combined_data_150k
	- This is the CSV File, that contains 150k cleaned data samples(50k from each pos, neg, and neut) required to train models. 
		> Can be downloaded from [here](https://drive.google.com/file/d/1p9wUMP7TE5vZqo2BunvJaE2wGXFm7Rsr/view?usp=sharing)  	
	- What data this file contains?
		> This file contains two columns text and target. 
		> Text can be neutral, positive, or negative.  
		> Target can be label 0, 1, 2 for neutral, positive, and negative respectively.    
