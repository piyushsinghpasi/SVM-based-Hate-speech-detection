# SVM based Hate Speech Detection
An implementation that uses support vector machine to classify text into either toxic or non-toxic class. Many variants, approximations of SVMs are implemented and analyzed to compare the effect of SVMs on the Binary classification Task of Hate Speech Detection.
*Platform* : Python Jupyter, Google Colab or VS Code.  
VS Code (version 1.59.0) was used to run the code. 

## Common libraries used in for the project
numpy (version 1.19.5)  
pickle (version 4.0)  
regex (version 2019.12.20)  
sklearn (version 0.24.2)  
chars2vec (version 0.1.7)  
keras (version 2.7.0)  
matplotlib (version 3.4.3)  
nltk (version 3.6.5)  
pandas (version 1.3.4)  
sentence-transformers (version 2.1.0)  
tensorflow (version 2.7.0)  
datasets library is used   
##### If any other dependency issue then please install from within notebook only using '!pip install package_name'

## Running notebooks in project
#### Before running the notebooks go to the google drive link below and download the Project folder for all models and data
https://drive.google.com/drive/folders/1vZEvqBAgGv-8quZ7Enrv8HNELiD4E7wl?usp=sharing
#### Once downloaded please adjust the ingestion path in the notebooks to point to correct location accordingly.
For each Notebook in Code folder:  
Run all the cells for training and testing of SVM model.

##### Caution:
Run all cells for functions to be defined, Note and Cautions are mentioned in the Notebook as well

## References

https://www.kaggle.com/eikedehling/feature-engineering<br>
https://www.analyticsvidhya.com/blog/2021/04/a-guide-to-feature-engineering-in-nlp/<br>
https://keras.io/getting_started/faq/#how-can-i-obtain-the-output-of-an-intermediate-layer-feature-extraction<br>
https://www.kaggle.com/jpmiller/augmenting-the-data<br>
https://github.com/keunwoochoi/transfer_learning_music<br>
https://github.com/keras-team/keras/issues/2588<br>
https://github.com/keras-team/keras/issues/6090<br>
https://github.com/UKPLab/sentence-transformers<br>
https://scikit-learn.org/stable/modules/kernel_approximation.html<br>
https://stackoverflow.com/questions/23056460/does-the-svm-in-sklearn-support-incremental-online-learning<br>
https://towardsdatascience.com/how-to-make-sgd-classifier-perform-as-well-as-logistic-regression-using-parfit-cc10bca2d3c4<br>
https://stackoverflow.com/questions/51495819/how-to-plot-svm-decision-boundary-in-sklearn-python<br>
https://stackabuse.com/implementing-svm-and-kernel-svm-with-pythons-scikit-learn/<br>
https://www.datacamp.com/community/tutorials/svm-classification-scikit-learn-python
