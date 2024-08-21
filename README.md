Aim🎯:
    To create a Machine Learning(ML) model to predict whether the tweets belong to a violence or not, in the form of 1 or 0.This is a classic case of a Binary Classification problem.
    Additionally I have also created a Deep learning model for the same problem statement.


Procedure🎈🎈:
          
          * For machine learning model of Natural Language Processing(NLP), first we have to import the necessary packages.Incase of no such package available in the local machine.
          Need to download and install it.Then we have to load and read the Dataset needed for the model creation.After that we have to do exploratory data analysis.
          Once the data analysis is done we have to pre-process the data as per our need.The pre-processing methodologies includes Data Cleaning,Tokenisation,Stopword Removal and Lemmatisation.
          
          *After performing the pre-processing functionalities,we should combine the list of text into the required tweet format.
          Then we need to transform the text into a meaningful vector (or array) of numbers.This can be done by creating Bag Of Words using various techniques.
          But the techniques I used in the model is Counter Vectorizer and TF-IDF Vectorizer.Among these two Counter Vectorizer works fine for this kind of Data-Set.
          So I used Counter Vectrized Data for building the model.
          
          *Finally,the text classification model is ready to be build, with various most-commonly used algorithm such as LogisticRegression(),Naives Bayes(MultinomialNB()),SVC(),
          DecisionTreeClassifier() and last but not least RandomForestClassifier().I have built the model with each algrithm specified above and evaluated them individually with
          various evaluation metrics such as Cross Validation(cross_val_score),Classification report and Confusion matrix to get the accuracy of the model on each algorithm to choose the best one among them.
          Atlast after evaluation,I have built the model with the desired algorithm to make predictions.

          *while considering the Deep Learning Model,first we have to import necessary packages,then loading data and making exploratory data analysis is performed.After that tokenisation should be done.
          Then the processed tweet should be converted to vector of sequence(Padded_Sequences) using padding and truncation.After that the model can be created with different layers of neural networks.
          I have created a sequential model with one embedded layer,two bi-directional layers along with LSTM activation functions and one dense layer(Output layer) with softmax activation function.
          Used adam optimizer,sparse_categorical_crossentropy for calcualting loss function and accuracy evaluation metrics to evaluate the model.Atlast, the model was fit with validation data,callbacks and monitor arguments.
          Then I have trained the model with 10 epochs along with early stopping,so that once getting highest accuracy the epoch will be stopped automatically.Then the model is ready to make predictions.

          *Finally,both ML Classification model and DL classification model have been built to make predictions, whether the tweet is violent or not.To get clear understanding of procedure kindly refer to the notebooks above.
          The line by line explanation and deep procedural explanation is given in the Notebook file itself.The functions(pre-defined and user-defined functions) used for this project is also explained in the notebook.
          I have also attached the detailed accuracy report summary of both the models in Excel work-book format, in the main branch of this project.


Result🎉🎉🎉:
       The machine Learning(ML) model to predict whether the tweets belong to a violence or not is built successfully with RandomForestClassifier() algorithm.Among the other algorithms 
       it is the one which gives highest accuracy of 96%.Considering Deeep Learning model the sequential model worked fine and it gives 100% accuracy in the 7th epoch itself while training the model.
       So the DL model is built with sequential model along with the above mentioned layers.

          


          
          
          

