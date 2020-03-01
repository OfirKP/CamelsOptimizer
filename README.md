# CamelsOptimizer :camel:
Yet another camel case.
Finding the optimal person to be traded for camels using _Bayesian Optimization_, 
according to the scores in [this site](https://kamelrechner.eu/en/result).

## Motivation
After playing and having fun with the [site](https://kamelrechner.eu/en/result), we decided to find the optimal person to be traded for camels (who is worth the largest number of camels).

At first, we tried _Grid Search_, but it was too long because there are 4,432,320 permutations for choosing a person.
Therefore, we decided to use the _Bayesian Optimization_ algorithm to achieve faster results, using the [Hyperopt](https://github.com/hyperopt/hyperopt) library.

## Usage
Open the [notebook](optimizer.ipynb) in your favorite environment.

Install the required packages, run the cells and change the parameters according to your liking.

## Results
After running the algorithm for 4800 iterations, the following result was acheived (male):
```
Best Results
===================
Score is 106.0
age: 26
beard: middle
body: muscle
eyecolor: blue
hair: middle
haircolor: blonde
height: 178
```

![image](https://user-images.githubusercontent.com/11351634/75630081-410ef780-5bf0-11ea-8dae-299e63c7bbcc.png)

## Disclaimer
This project was created for educational purposes only. No camel was harmed during the scripting :camel:.
