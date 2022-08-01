# Machine Learning Credit Risk

## Overview

This analysis is made with the intention of determining if credit risk machine learning prediction is viable.

##Results

- Oversampling

The oversampling method seems a little lacking as its accuracy score is only 64%. The recall rate supports this as well.

![image](https://user-images.githubusercontent.com/101848882/182060516-7cf148e9-fb1d-4ec0-9055-387cbc393678.png)


![image](https://user-images.githubusercontent.com/101848882/182060471-54d65fa3-1d42-49cf-b0e9-22308e155f5c.png)

- SMOTE Oversampling

The SMOTE oversampling still has a low accuracy score with 65%. It has an even lower recall rate in .63.

![image](https://user-images.githubusercontent.com/101848882/182060819-bbdf3434-aaf4-425e-b9b5-fc7f893665de.png)

- Undersampling

The undersampling method has a 54% accuracy score, which makes it the less reliable method so far.

![image](https://user-images.githubusercontent.com/101848882/182061416-4804a3cf-92a8-4d0a-a472-665a656bcf8c.png)

- Combination of Over and Under Sampling

This machine learning method is right around both oversampling method in accuracy. It is still not something I would personally recommend as a 35% chance of approving loans of approving risky loans is still too risky.

![image](https://user-images.githubusercontent.com/101848882/182062095-478f80e0-0921-4af5-865c-32f98934f733.png)

- Random Forest Classifier

This is the more successful model so far. I would feel confident recommending this model to a client. An 87% accuracy score makes it a very powerful prediction tool.

![image](https://user-images.githubusercontent.com/101848882/182062953-13544f0d-c7bd-4a5a-97eb-57f2d7785dec.png)

- AdaBoost Classifier

The AdaBoost optioin seems like the most accurate model with a 93% accuracy ratio.

![image](https://user-images.githubusercontent.com/101848882/182063695-e895030f-c770-476a-9fd7-77f553412c1a.png)

## Summary

After analyzing all 6 machine learning models, the AdaBoost was the best fit for this particular dataset. It makes sens when considering that credit risk analysis takes into consideration a great number of variables. An iterative and self actualizing algorithm like this seems like a perfect fit and I would recommend it to our clients without a doubt.
