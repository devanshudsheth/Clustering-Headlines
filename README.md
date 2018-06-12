# Clustering-Headlines
<<<<<<< master
We were given a Newspaper article in Spanish with multiple columns. 
Our aim was to cluster similar news headlines together. 
We developed python scripts for executing this project. 
We converted the PDF document into an HTML used PDFMiner for extracting text.
For handling information with respect to HTML document we used beautiful soup to make the necessary formatting and further enable us to perform k-means clustering. We used for nltk of python to perform stemming, removing stop words and tokenization.
We calculated the cosine distance which (1 – cosine similarity). 
The similarity was calculated using TF-IDF. 
The TF-IDF matrix was developed from the TF-IDF Vectorizer which converts the stemmed words to vector space. A method called MDS was used for cluster visualization. 
It would develop a scatter plot.
=======
1. Convert the pdf file into an HTML file using the command
    
    os.system("pdf2txt.py -o spanishTest.html -t html spanishTest.pdf")

2. Run project_v2.py
3. Run kmeans.py
4. Run translate.py
>>>>>>> master
