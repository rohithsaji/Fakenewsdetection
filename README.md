# Fakenewsdetection
Testing two types of preprocessing techniques on a CNN-RNN hybrid model for Fake news detection.

Datasets implemented on:
- [ISOT dataset](https://pages.github.com/)
- [Covid-19 dataset](https://www.kaggle.com/elvinagammed/covid19-fake-news-dataset-nlp)

**Note** : *All datasets have been included.*

Types of preprocessing used:
- onehot tokenizer from keras with pre-padding.
- tokenizer from keras with post padding & gloVe pre-trained embeddings.

## Results
The following are the accuracy results for the datasets:
- **ISOT dataset**
  - gloVe model: 99%
  - onehot model: 99.22%
- **Covid-19 dataset**
  - gloVe model: 94.25%
  - onehot model: 91.17%
  
## Graphs
**Note** : *The following graphs are for ISOT dataset.*

### gloVe Model
![graph](https://github.com/rohithsaji/Fakenewsdetection/blob/master/Results/ISOT/Graph-Glove.png?raw=true)
### onehot model
![graph](https://github.com/rohithsaji/Fakenewsdetection/blob/master/Results/ISOT/Graph-onehot.png?raw=true)

**As seen from the grpahs above training & validation accuracy is steadily increasing and training & validation loss is steadily decreasing, so the model has not overfitted.**
