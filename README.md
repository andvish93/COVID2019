# COVID2019
Analyzing COVID-19 publications and summarizing the publications across topics

## Dependency
  ### 1.) Libraries Needed
  Pandas, Numpy, NLTK, Scapy, Matplotlib, String, Sklearn, Networkx
  
  ### 2.) Files Needed
  
  a) Download XML File
  Link: https://github.com/midas-network/COVID-19/tree/master/documents/mendeley_library_files/xml_files
  
  Download the mendeley_document_library_2020-03-25.xml File and place in the notebook directory.
  
  b) Download GloVe Word Embeddings
  GloVe: https://nlp.stanford.edu/data/glove.6B.zip
  
  !wget http://nlp.stanford.edu/data/glove.6B.zip
  !unzip glove*.zip
  
  Download the the zip file and unzip in the same directory where Python notebooks are downloaded.
  
## Files Included
  ### ClusterData.ipynb: Perform data preprocessing and identifies the cluster of Topics
  ### Topics.ipynb: Summarizes the topic
  ### Summarizer.ipynb: Generates one liner for each topic
  
## How To Run
  1.) Download the XML file and GloVe
  2.) Run the Notebook in the below order:
    a.) ClusterData.ipynb
    b.) Topics.ipynb
    c.) Summarizer.ipynb
