# Covid_Geo_LLM_Analysis

This repository serves as a public documentation of, currently, the various scripts used for the COVID-19 Infoveillance Research Project conducted by Dr. Christian Lopez Bencosme and David Broczkowski.
This research project utilizes the [COVID_19_Tweets dataset](https://github.com/lopezbec/COVID19_Tweets_Dataset) from the paper “An Augmented Multilingual Twitter dataset for studying the COVID-19 infodemic” authored by Dr. Lopez and Dr. Gallemore. 
Please note that for security reasons, the paths and structure of the scripts may be missing or manipulated. 

## Abstract
Social media has proven to be a valuable resource as an indicator throughout worldwide events such as the COVID-19 pandemic. This study proposes the utilization of social media posts to determine whether analyzing these posts can provide a significant lag correlation to daily cases of COVID-19, in turn providing an early indication of the pandemic's trends compared to the report of official case numbers. This study utilizes an LLM to create predictions and extract information from social media posts. The [COVID_19_Tweets dataset](https://github.com/lopezbec/COVID19_Tweets_Dataset) is used as a source of social media posts.

## Organization
The various scripts are separated into 3 categories: Python, SLURM and Terminal scripts. 

Python scripts are based in Python are were used to handle the reading and manipulating of files of the dataset. 
SLURM scripts are based in Linux and were used to perform operations on the files, including passing to the python scripts, that necessitated communication to Lafayette College's High Performance Cluster (HPC). 
Terminal scripts are based in Linux and were used to call various SLURM scripts. 

Each category has a high level document detailing the function of each script. 

## References

Lopez, C. E., Gallemore, C., “An Augmented Multilingual Twitter dataset for studying the COVID-19 infodemic” Soc. Netw. Anal. Min. 11, 102 (2021). DOI: s13278-021-00825-0 https://pubmed.ncbi.nlm.nih.gov/34697560/

