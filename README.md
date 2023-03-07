# b-ann-k-churn
Using Deep Learning (ANN) to predict Bank Churn

* Performed Data Preprocessing techniques to clean and make the data ready for model building

* **Exploratory Data Analysis** was used to discover insights in the data

* Modelled the data with Deep Learning (ANN architecture)

* Performed regularization using DropOut

____
## Results

ANN of 30 epochs with 4 layers consisting of
* 32
* 64
* 32
* 1


| Data    |  Accuracy |  AUC   | Loss |
|---------|-----------|--------|------|
| Train    |  0.87 |  0.88   |  0.3070 |
| Test    |  0.85 |  0.86   |  0.3388 |

___

Regularized ANN of 30 epochs with 4 layers consisting of
* 32
* 64 with 50% Dropout
* 32 with 20% Dropout
* 1


| Data    |  Accuracy |  AUC   | Loss |
|---------|-----------|--------|------|
| Train    |  0.87 |  0.87   |  0.3251 |
| Test    |  0.86 |  0.86   |  0.3375 |

___
## Model Deployment
The final model with the best score was deployed on a web application built with **Django** with the frontend built with **HTML & CSS** with **Boostrap 4** as the CSS Framework.

![Web application of the model](Plots/app.png)


___
