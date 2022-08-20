<b>First Project of Dog Breed Classification using CNN</b>

For Dog Breed Classification, we have used the TensorFlow to build a Convolutional Neural Network that will help you to identify the breed of a dog from its image. In the process, we will use Transfer Learning and learn how to design, train and test models with the provided dataset. Achieved an accuracy of 73% using VGG-16 and Transfer learning.

Dataset: "https://www.kaggle.com/c/dog-breed-identification/data"

File descriptions

train.zip – the training set, you are provided the breed for these dogs.
test.zip – the test set, you must predict the probability of each breed for each image.
sample_submission.csv – a sample submission file in the correct format.
labels.csv – the breeds for the images in the train set.
Libraries
The list below represents main libraries and its objects for the project.

PyTorch (Convolutional Neural Network)
Tensorflow
Matplotlib (Plot Images)
Numpy


<b>Second Project of Text Summarization in NLP</b>

The objective of this project was to build an Abstractive Text Summarizer using Sequence-to-Sequence Recurrent Neural Networks. For this project Amazon Fine Food Reviews dataset from Kaggle was used which has 500,000 reviews from 1999-2012. In the modern Internet age, textual data is ever increasing. We need to condense this data while preserving the information and meaning. We need to summarize textual data for that.
Text summarization is the process of automatically generating natural language summaries from an input document while retaining the important points. It would help in easy and fast retrieval of information. Abstractive summarization systems generate new phrases, possibly rephrasing or using words that were not in the original text.

During implementation a 3 Layer Stacked LSTM Encoder-Decoder model with Global Attention Mechanism was used. With this model I was able to get an accuracy of 65.89% on training set (constituting 80% of the dataset).

Dataset: "https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews?resource=download"

Libraries:

Pandas
Re
gensim
Tensorflow
