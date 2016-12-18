##A Simple Text Retrieval System

Documents and query are represented as vectors. Text Documents are retrieved based on Cosine similarity of document and query vector, which is an array of TF-Idf score of the terms.

For fun, I have included a Prpgress bar in the createIndex.py code.

First run the create index program:

        python createIndex.py

Then run the query index program:

        python queryDoc.py pq 
        
To run the query file, specify the the type of query 
pq - phrase query
ftq - free text query

english_stopwords.txt is the stopwords file
Index_db.json - the inverted index of the corpus, stores the term and corresponding posting list
index_score_db.json - is the tf-idf database for each word


![Index Creation](/IR-Vector-Space-Model/demo_images/index.JPG)

![Index Read and Query](/IR-Vector-Space-Model/demo_images/query.JPG)