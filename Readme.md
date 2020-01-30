# Fashion Text Analytics
The input dataset is a sample of fashion reviews crawled from Vogue during Fashion Week. The main content is the review text. The file also contains meta data such as “year”, “season”, “brand”, “author of review.”
The jupyter notebook will scan through the review texts and performed some basic text analytics to identify key trends of fashion in 2016
## Imports:
For the file to run smoothly, make sure to import the following packages:
import numpy as np
import pandas as pd
import nltk
from nltk import FreqDist
from os import path
from PIL import Image
from wordcloud import WordCloud, STOPWORDS, ImageColorGenerator

import matplotlib.pyplot as plt
%matplotlib inline
## Usage:
The file will go through the review texts and plot the top 30 words:
* Through a simple bag of words approach
* With stopword removal and Porter stemmer
* Focus on noun forms only
* Focus on proper nouns
* Bi-grams approach on top of stopword removal and Porter stemmer
* Tri-grams approach

## Written report:
For a written report of the findings, please refer to
