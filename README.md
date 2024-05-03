# NLP_Lab2

# NLP Analysis Notebook

This notebook presents a comprehensive analysis of text data using various Natural Language Processing (NLP) techniques. The analysis is divided into two main parts:

## Part 1: Rule-Based NLP and Regex
- **Bill Generation**: Utilizes regular expressions to parse and process text for generating itemized bills.
- **Data Cleaning**: Implements regex for tokenization and removal of stopwords and non-meaningful characters.

## Part 2: Word Embedding
- **Data Retrieval**: Fetches data from MongoDB for further processing.
- **Word Embeddings**: Applies pre-trained models like ArWordVec and FastText for word vectorization.
- **Visualization**: Employs t-SNE for dimensionality reduction to visualize word embeddings.

## Conclusion
The notebook concludes with insights on the distinct semantic and syntactic aspects captured by different word embedding models.

## Usage
To run this notebook:
1. Ensure you have `nltk`, `pymongo`, `gensim`, `fasttext`, `sklearn`, and `matplotlib` installed.
2. Download the required pre-trained models as mentioned in the notebook.
3. Execute the cells in sequence to perform the analysis.

**Note**: The notebook includes code for data preprocessing, model application, and result visualization. Adjust the parameters as needed for your specific dataset.
