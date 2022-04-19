# IR-1-Search-Engine-for-song-lyrics-
IR Assignment 1

CS F469 - Information Retrieval 

Assignment – 1: Domain Specific Search Engine

Language Used: Python

Aim:
To make a search engine that retrieves relevent documents when a query is entered using the vector space model and "tf-idf" score for ranking.

Dataset Used:
The dataset for the search engine is obtained from the Kaggle. It consists of "Song name", "Artist", "year of production" and the "lyrics". The dataset is of the format CSV(Column seperated Vectors) with 5 columns - Doc-Id, Song, Artist, Year, Lyrics.

Working Model:
The search engine can be started by running main.py.
The entire corpus is preprocessed and the tf-idf Table is produced.
Enter the words or phrases in lyrics you want to search for.
After each search, the top 10 documents that matches with the query will be displayed.
The results will be random if the searched words are not present in any document in the corpus.
On clicking the Document, one can view the entire document with details like 'artists' etc.

Requirements/Installation:
To run the following code, Flask and nltk have to be readily installed.

Flask can be installed by following the documentation in the below link. https://linuxize.com/post/how-to-install-flask-on-ubuntu-18-04/
ntlk can be installed using ‘ntlk.download()’ in a python shell or in the program.
(This is a collaborative team work in which the UI has been handled by a teammate)
