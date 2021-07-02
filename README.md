# TEXT ANALYSIS AND SARCASM DETECTION ON NEWS DATASET
## INTRODUCTION
### Humans are born with a social nature that allows us to interact with one another in positive or harmful ways. Sarcasm may be both positively hilarious and negatively nasty, and it is an important part of human connection. However, determining whether someone is making fun of us or admiring us can be tricky at times. So, in order to detect sarcasm quickly, I’ll need to create a model that can detect sarcastic language.
## PROBLEM STATEMENT
### My goal is to predict if a given text is sarcastic or not using the News Headlines Dataset. This dataset for detecting sarcasm in news headlines was compiled from two news websites. We compile factual (non-sarcastic) news headlines from various publications.
## DATASET
### The dataset provided has 2 independent variables and 1 dependent variable:

### Independent Variables
### 1.	article_link (type: Object): contains links to the news articles.
### 2.	headline (type: Object): contains headlines of the news articles.

### Dependent Variable(type: categorical) - is_sarcastic -> 0 = Non-sarcastic text, 1 = Sarcastic text

### Source Code used in the Project is Python. Therefore, just install the following libraries/packages before running the code.

### To run code in Python, following are the packages which needs to be installed followed by the command to be executed on the PowerShell/Terminal before executing the code successfully – 
### 1) numpy – pip install numpy
### 2) pandas – pip install pandas
### 3) matplotlib – pip install matplotlib
### 4) seaborn – pip install seaborn
### 5)threading – pip install threading
### 6)	requests – pip install requests
### 7)	Beautiful Soup 4 – pip install bs4
### 8)	Regex – pip install re
### 9)	String - pip install string
### 10)	NLTK – pip install nltk
### 11)	Wordlcoud - from wordcloud import WordCloud, STOPWORDS, ImageColorGenerator
### 12)	Textblob – pip install textblob
### 13)	sklearn – pip install sklearn