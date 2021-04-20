# Advanced Machine Learning Projects

*******************************************************

### Repository of independent deep learning projects I have completed

#### Predicting U.N. World Happiness

[<img src="https://olatorera.com/wp-content/uploads/2020/03/world-happiness-report.png" width="200">](https://worldhappiness.report/)

<br>

Data comes from [Gallup World Poll](https://worldhappiness.report/).

Project files:

- world-happiness-models.ipynb
  - Models predicting whether a country has a happiness rating of "Very High", "High", "Average", "Low", or "Very Low". 
  - Trained models included: Sequential Keras model, Random Forest, Gradient Boosting, XGBoost, and SVM.
  - SVM had the best performance, with an accuracy and f1-score of .53. Important to note is that the dataset is relatively small with about ~200 observations, each row corresponding to one country.
  

- world-happiness-models.html
  - knitted output file from world-happiness-models.ipynb
  
  
*******************************************************


#### Predicting Covid-19 Using X-Ray Images

[<img src="https://www.princeton.edu/sites/default/files/styles/scale_1440/public/images/2020/05/x-ray-image-2b_full.jpg?itok=2FO93vqG" width="200">](https://ieeexplore.ieee.org/abstract/document/9144185)

<br>

Data comes from [Chowdhury et al.'s 2020 study, “Can AI help in screening Viral and COVID-19 pneumonia?”](https://ieeexplore.ieee.org/abstract/document/9144185)

Project files:

- covid19-xray-models.ipynb
  - Neural network models predicting whether an X-ray image is "Covid-19", "Normal", or "Pneumonia"
  - The best performing models were the Sequential and ResNet neural network models. Both received **96% on all metric fields**, including accuracy, f1-score, precision, and recall.
  - Other trained models include: Squeezenet, Squeezenet with batch normalization, and VGG16.


- covid19-xray-models.html
  - knitted output file from covid19-xray-models.ipynb


*******************************************************


#### Predicting Covid-19 Misinformation Tweets

[<img src="https://www.docwirenews.com/wp-content/uploads/2021/01/GettyImages-1213869400.jpg" width="200">](https://www.sciencedirect.com/science/article/pii/S2468696420300458)

<br>

Data comes from [Shahi et al.'s 2021 study, “An exploratory study of COVID-19 misinformation on Twitter”](https://www.sciencedirect.com/science/article/pii/S2468696420300458)

Project files:

- covid_misinformation_tweets_models.ipynb
  - Deep learning models predicting whether a tweet on Covid-19 is "real" or "fake"
  - The best performing model was the Stacked Recurrent Neural Network (RNN) model achieving **95% on all metric fields**, including accuracy, f1-score, precision, and recall.
  - Other trained models include: Seqeuntial Model with Emedding and 1D Convnet layers, a Bidriectional LSTM model, Long Short-Term Memory (LSTM) Sequential Model with Embedding layer and Dropout, a Recurrent Neural Network (RNN) model, and a Glove Embedding layers model.


- covid_misinformation_tweets_models.html
  - knitted output file from covid_misinformation_tweets_models.ipynb
  
 *******************************************************


#### Flower Classifier

[<img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fmedium.com%2F%40bernardt.duvenhage%2Fpytorch-scholarship-challenge-from-facebook-flower-classifier-d3623a9fab7c&psig=AOvVaw3VSDXqe2XHSYQ4jE38Guqw&ust=1618974619583000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKDfisvsi_ACFQAAAAAdAAAAABAD" width="200">](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html)

<br>

Data comes from [Nilsback and Zisserman's 2008 study, “Automated flower classification over a large number of classes”](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html8)

Project files:

- Flower_Classifier.ipynb
  - Deep learning models predicting whether the classification of flowers
  - The best performing model for the three class classifier was the Squeezenet model, with an AUC of 0.99 and accuracy of 0.98.
   - The same model archetecture performed well with classifying all 102 flower clases, with an AUC of 0.95 and accuracy of 0.57. I will continue to optimize and train this model to achieve better performance.


- Flower_Classifier.html
  - knitted output file from Flower_Classifier.ipynb
