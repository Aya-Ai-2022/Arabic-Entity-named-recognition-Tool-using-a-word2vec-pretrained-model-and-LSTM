# Arabic-Entity-named-recognition-Tool-using-a-word2vec-pretrained-model-and-LSTM

* This project was created by [Aya ](https://github.com/Aya-Ai-2022),[Gehad ](https://github.com/Gehad-16 ) and [Rana](https://github.com/20180104Rana)

* This project aims to develop an Arabic Entity named recognition Tool based on a deep learning architecture combining a word2vec pretrained model and a Long Short-Term Memory (LSTM) neural network . 
* The objective of this tool is to automatically identify and classify named entities such as persons, organizations or locations in Arabic texts.

### **Implementation**
The implementation of the Arabic Entity named recognition Tool is done in Python using the keras library.

* The first step of the tool is to preprocess the input Arabic text by tokenizing , cleaning and embedding the words using a pre-trained word2vec model. The word2vec model learned from a large corpus of Arabic texts and provides a dense vector representation for each word in the vocabulary, which captures semantic and syntactic information about the language.

* The second step of the tool is to feed the embedded words into a bi-directional LSTM, which is designed to capture the sequential context of the text and learn discriminating features for the named entity recognition task. The LSTM model is trained on annotated Arabic datasets with named entity tags (e.g. PER for person, ORG for organization, LOC for location).

* The third step of the tool is to evaluate the trained model on a test dataset and report the precision, recall and F1-score metrics for each named entity type. The performance of the model is compared to other state-of-the-art models in the literature on the same task.




