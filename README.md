# Keyword-Extraction-for-Pathology-Reports-with-BERT
This is Keyword extraction for pathology report based on the pre-trained BERT.  
Please visit the original repo of [BERT] (Devlin, et al.) for more information about the pre-trained BERT.

## For NOT programmer users
[KEP] is a web-based **keyword** **extraction** **tool** for pathology report.  
Users who are not familiar with python can use this tool.  
  
![screensh](./img/website.png)


## Environments

	python 3.6  
	pytorch 1.2.0  
	pytorch-pretrained-bert 0.6.2  

## Usage

Example:  

	python Keyword_Extraction_BERT.py --data sample.csv

Arguments:  

	--data			Data  
	--maxlen		Max Length  
	--bs			Batch Size  
	--lr			Learning Rate  
	--epoch			Epochs  
  
	
	
[KEP]: http://cdal.korea.ac.kr/KEP/kep.php
[BERT]: https://github.com/google-research/bert