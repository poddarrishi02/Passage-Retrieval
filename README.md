# Information-retrieval: Query Based Passage Retrival
This project focuses on retrieving relevant paragraphs/passages from a given corpus of policy documents based on user queries. The following steps were implemented:<br><br>
    <ol>
        <li><b>Tokenization and Normalization:</b> The corpus of policy documents was tokenized and normalized to break it down into paragraphs. Each paragraph was then mapped to the document it belonged to.</li>
        <li><b>Inverted Index Construction:</b> An inverted index was constructed to efficiently map each word to the indices of the paragraphs in which the word appeared. This indexing technique optimized the search process.</li>
        <li><b>Query Preprocessing:</b> Queries provided by users underwent the same tokenization and normalization process as the corpus. This ensured consistency in the data and improved search accuracy.</li>
        <li><b>Ranking Methods:</b> Two primary ranking methods were employed to determine the relevance of search results. The first method involved calculating the TF-IDF (Term Frequency-Inverse Document Frequency) score, while the second method relied on Word2Vec embeddings to capture semantic relationships between words.</li>
    </ol>
 <h1>Requirements</h1>
    <ul>
        <li>gensim==4.3.0</li>
        <li>nltk==3.8</li>
    </ul>
    <h1>How to Run</h1>
    <ol>
        <li>
          Clone the Repository/Download and unzip the folder.
        </li>
        <li>
           Install the above mentioned requirements.
           Using the commands:-
            <ul>
                 <li>pip install nltk</li>
                 <li>pip install gensim</li>
            </ul>
        </li>
        <li>
           Install the nltk libraries by running the following commands in the .ipynb file.
           Using the commands:-
            <ul>
                 <li>nltk.download('stopwords')</li>
                 <li>nltk.download('punkt')</li>
            </ul>
        </li>
        <li>
           Type any queries in the query section in the .ipynb file  
        </li>
        <li>
            Run the ipynb file in order from top to bottom.
        </li>
        <li>
            Output produced will be top 5 related paragraphs from the dataset using both tf-idf or doc2vec algorithms.
        </li>
    </ol>

