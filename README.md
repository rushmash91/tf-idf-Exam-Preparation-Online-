# Exam_Preparation_Online
### Keywords based on TF(Term Frequency)

## Overview
The script(main.py) extracts all text from the given **PDF** using PyPDF2. The text is then filtered for _Stopwords_, _Punctuations_ and _Header_
etc after being **Tokenized** with the help of nltk, strings and numpy. Term Frequency of the **Top 11** Keywords is calculated and plotted in a bar graph via matplotlib. A table 
is also given as output containing **Top 40** Keywords(tabulate).


![alt text](bargraph_for_top_12_keywords.png "Frequncy of TOP 11 Keywords")

### Top 40 Words

|**Keyword**  | **Frequency**
|------------ | -----------
|java         |         83
|data         |         43
|button       |         35
|int          |         29
|code         |         28 
|applet       |         27
|class        |         26
|array        |         24
|string       |         22
|public       |         21
|c++          |         21
|method       |         19
|example      |         18
|object       |         18
|objects      |         17
|c            |         16
|language     |         14
|c/c++        |         13
|use          |         13
|return       |         13
|may          |         12
|memory       |         12
|garbage      |         11
|program      |         11
|browser      |         11
|void         |         11
|primitive    |         11
|types        |         11
|ocate        |         11
|applets      |         10
|following    |         10
|applications |          9
|comments     |          9
|make         |          9
|file         |          9
|reference    |          9

## Dependencies

- PyPDF2
- nltk
- matplotlib
- numpy
- tabulate
- string

