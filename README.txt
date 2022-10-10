About
-------
This project was developed to fulfill data analysis, visualization, sentiment analysis and classification of a twitter datase.

Installation
-------------
Please use the package manager pip or pip3 depending on your python version to install relevant libraries and frameworks used.

You will need to download and load the 1.6GB "word2vec-google-news-300" bin file using the gensim downloader, code syntax to automatically do this is under the Word2vec section, this might take some time but it runs perfectly well. This wasn't attached to submission due to file size and extensive upload time.

Usage
------
In order to run the software deliverable the following files must be in the same folder as the "Twitter_Sentiment_Analysis_Using_Bag_Of_Words_and_Word2vec_Features.ipynb" file:

1. dataset.csv


Depending on your IDE, selecting run all, re-runs all code execution. At times, results can vary but always marginally.

For best visualiztion put IDE in light mode for clearer images and graph labels.

Execution
----------
The code executes as follows:
1. Dataset is collected
2. Preprocessing is carried out
3. Statistical analysis takes place
4. Visual analysis is executed
5. Bag-of-word results are provided
6. Word2vec results are provided

Notes
-----
There is no leakage between train and test sets as they are split before being input to the differing classifiers

Execution can be time consuming due to cross-validation

If SVM using Word2vec fails to run or converge, a couple reattempts would resolve this

Contact
--------
okosunprincewill@gmail.com