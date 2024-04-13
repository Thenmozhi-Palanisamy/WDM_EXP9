### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 12.4.24
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

![image](https://github.com/Thenmozhi-Palanisamy/WDM_EXP9/assets/95198708/8d3495e3-6371-4bbb-9d79-f2cf34ec3d5e)

![image](https://github.com/Thenmozhi-Palanisamy/WDM_EXP9/assets/95198708/119e22e0-6848-499c-a1d8-2d1786e258d8)

![image](https://github.com/Thenmozhi-Palanisamy/WDM_EXP9/assets/95198708/6df410bc-3dbd-4dba-b5ed-5dc1b05294b3)

![image](https://github.com/Thenmozhi-Palanisamy/WDM_EXP9/assets/95198708/889c1975-0dba-458a-b477-26118e7807fb)



### Result:

Thus, the preprocessing technique on Twitter Data using Rapidminer is implemented successfully.


