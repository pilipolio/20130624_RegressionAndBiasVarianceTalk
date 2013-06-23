## Outline

 - [Linear regression in the frequentist context](http://nbviewer.ipython.org/urls/raw.github.com/pilipolio/20130624_RegressionAndBiasVarianceTalk/master/LinearRegression.ipynb)
 - Iterative algorithms and the LARS algorithm
 - Penalisation, shrinkage and the connection with the Bias-Variance trade-off
 - [Example on real data set](http://nbviewer.ipython.org/urls/raw.github.com/pilipolio/20130624_RegressionAndBiasVarianceTalk/master/DiabeteExample.ipynb)
 
## Bibliography

 - On-line video lectures from [mathematicalmonk's YouTube channel](http://www.youtube.com/user/mathematicalmonk) :
    - [Maximum Likelihood Estimation](http://www.youtube.com/watch?v=aHwsEXCk4HA&list=PLD0F06AA0D2E8FFBA&index=22)
    - [Linear regression](http://www.youtube.com/watch?v=kdAGH6mtNAM&list=PLD0F06AA0D2E8FFBA&index=53)
    - The [Bias-Variance decomposition](http://www.youtube.com/watch?v=C3nIFH649wY&list=PLD0F06AA0D2E8FFBA&index=70)
    - [Model selection](http://www.youtube.com/watch?v=rW0B8o7JtFk&list=PLD0F06AA0D2E8FFBA&index=74)
    
 
 - The [lasso/lars page](http://www-stat.stanford.edu/~tibs/lasso.html) of Tibshirani and the [original Lasso paper](http://www-stat.stanford.edu/~tibs/lasso/lasso.pdf);
 - The [Annals of statistics 2004](http://projecteuclid.org/DPubS?service=UI&version=1.0&verb=Display&handle=euclid.aos/1083178935) LARS paper (with blurred figures!)
 - An [earlier pre-print](http://www.stanford.edu/~hastie/Papers/LARS/LeastAngle_2002.pdf) of the LARS paper with nice vectorial figures
 - [LARS Slides](http://www.stanford.edu/~hastie/TALKS/bradfest.pdf) from Hastie
 
## Backlog

 - [x] Formulation of linear regression and MLE
 - [ ] Schematic geometrical view of linear regression
 - [x] Forward stepwise algorithm illustration
 - [ ] Full formulation of LARS algorithm
 - [ ] LASSO modification of LARS algorithm
 - [x] Illustration of LARS algorithm (could be improved by pgf/tikz?)
 - [ ] Group lasso/ridge toy examples (too similar)
 - [x] Illustration of regularisation path, MLE, Lasso/Ridge comparison
 - [x] Differenciate lasso/ridge paths?
 - [ ] Model selection introduction
 - [x] Formulation of Bias-Variance 
 - [ ] Link between Bias-Variance, model complexity and overfitting/generalisation
 - [x] Refactored contour plots