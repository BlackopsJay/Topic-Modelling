# Topic-Modelling with Artificial Intelligence 
This is a project on document clustering, on the applications of Artificial Intelligence in the world. making use of state of the arts clustering techniques
I explored the application of various techniques in the field of artificial intelligence to perform topic modelling. methods such as KMeans clustering, UMAP (Uniform Manifold Approximation and Projection), CountVectorizer, BERTopic, and NMF (Non-Negative Matrix Factorization) to extract meaningful topics from a collection of documents.
Data Accqusition, I manually downloaded several journals, relating to artificial intelligence from the web of science website.
Data Processing:After exploring my data, I created a model, to clean up my data, remove empty columns and stop words furthermore, my dataset was lemmatized, so as to enable the model read it 
KMeans Cluster: KMeans clustering is an unsupervised machine learning technique that partitions data points into clusters based on their similarity. I applied KMeans to group similar documents together, thereby identifying common topics.

UMAP: Uniform Manifold Approximation and Projection (UMAP) is a dimensionality reduction technique used for visualization and clustering. I utilize UMAP to visualize the document clusters in a lower-dimensional space, helping us gain insights into the distribution of topics.

CountVectorizer: CountVectorizer is a text preprocessing technique that converts a collection of text documents into a matrix of token counts. We use CountVectorizer to prepare our text data for topic modelling algorithms.

BERTopic: BERTopic is a modern topic modelling technique that leverages transformer-based language models such as BERT. It captures semantic relationships between words and documents to generate meaningful topics.

NMF (Non-Negative Matrix Factorization): NMF is a matrix factorization technique that is often used for topic modelling. It factorizes a term-document matrix into two matrices representing term-topic and topic-document relationships.

## Getting Started
Clone this repository to your local machine using git clone: gh repo clone BlackopsJay/Topic-Modelling
Set up your environment with the required libraries listed in the project notebooks.
Navigate to the notebooks directory and open the notebooks in a Jupyter environment or google collab.
Follow the step-by-step instructions in each notebook to implement the topic modelling techniques.
Experiment with different hyperparameters, visualizations, and evaluation methods to refine your results.
Refer to the notebooks for detailed explanations, code examples, and visualization techniques.

##Dependencies
#Make sure you have the following libraries installed:
Nltk
Flair
Bertopic
sklearn
transformers 
matplot
By applying various artificial intelligence techniques like KMeans clustering, UMAP, CountVectorizer, BERTopic, and NMF to topic modelling, we gain valuable insights into the underlying themes present in our text data. These techniques provide different perspectives and help us explore the data from multiple angles, enhancing our understanding of the content and its structure.

Feel free to experiment, modify, and extend the project as you see fit. Happy topic modelling!
