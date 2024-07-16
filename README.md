# Text Summarization using the TextRank Algorithm (with Python implementation)

- TextRank is an extractive and unsupervised text summarization technique, which ia inspired by PageRank Algorithm,
  which is used primarily for ranking web pages in online search results.
- Let’s take a look at the flow of the TextRank algorithm

  <img width="752" alt="Screenshot 2024-07-05 at 8 46 32 AM" src="https://github.com/nishtha2405/Text_Summarization/assets/76462489/e8fa6e58-8e7c-4af0-9918-60d7a7d084c3">
- The first step would be to concatenate all the text contained in the articles
- Then split the text into individual sentences
- In the next step, we will find vector representation (word embeddings) for each and every sentence
- Similarities between sentence vectors are then calculated and stored in a matrix
- The similarity matrix is then converted into a graph, with sentences as vertices and similarity scores as edges, for sentence rank calculation
- Finally, a certain number of top-ranked sentences form the final summary

##### Note : This project is essentially a single-domain-multiple-documents summarization task, i.e., we take multiple articles as input and generate a single bullet-point summary. Multi-domain text summarization is not covered in this project.

### You can download the dataset from here : https://drive.google.com/file/d/1HPShiXSrHMNlfcMZn-WFYjoftitOH9fJ/view

## Libraries Used:
- Numpy
- Pandas
- re
- NLTK
- Networkx

