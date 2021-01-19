## Text classification

This repository has been created with the aim of collecting different types of text classifications. Each of the booklets in this repository has been developed with high flexibility and generality, which can be used in different applications and different issues.

Description of the booklets:

### ***SKlearn library based solution***

This booklet uses the simplest and most intuitive elements in the [sklearn](https://sklearn.org/) library to develop a discriminant pipeline for a variety of texts.
The main advantages of using this method:

* Simple and intuitive
* High generality (simplicity of classification)
* The quality of work is not so much related to the quantity of data
* Very high speed when serving the model



### ***Transfer Learning based solution***

Transfer learning can be considered as the greatest revolution in the world of natural language processing from the beginning days until now.

The main advantages of using this method:

* Use the latest method
* The pre-training or learning phase (Unsupervised learning)
* High generality against genre and texture change
* Much less sensitivity to unbalanced classes



### ***More precise adjustment of the pre-trained model***

In this booklet, it is possible to retrain (fine-tune) the embedding vecotrs of the model. **All hyperparameters in the booklet are the result of developer experiments.**
Adapted from this [article](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjP0_aMvajuAhURPOwKHT7_ByYQFjAAegQIBxAC&url=https%3A%2F%2Farxiv.org%2Fabs%2F1801.06146&usg=AOvVaw2FNx0vgMxhtRs1UgRSALQg).