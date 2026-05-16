### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 16-05-2026
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:
<img width="1920" height="1078" alt="{EABD3B86-4F3E-4D6B-B1A2-82EB0EB7F93C}" src="https://github.com/user-attachments/assets/c0dc0104-5667-4d82-8475-89b008185ce9" />

<img width="1917" height="1084" alt="{844850B1-2069-46CC-A772-69DA299CECBD}" src="https://github.com/user-attachments/assets/19bcffb8-9a0c-487c-95e1-ce997fd9f3bf" />
<img width="1918" height="1087" alt="{F2D4C019-E50E-4AAF-8771-1B094439C66D}" src="https://github.com/user-attachments/assets/62bb7ecf-11ff-48a4-8612-9c27e6b02425" />

### Result:
Thus the experiment to implement preprocessing technique on Twitter Data using Rapidminer is done successfully.
