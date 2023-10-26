# PRML-final-project
This project is my final project in PRML class. It uses different models to get the earthquakes prediction.<br />
I used a linear model(gaussian conjugate)/Gaussian model(factorize prior with gamma function)/Dirichlet model(change prior into Dirichlet distribution) to run the regression<br />
Due to the intractable evidence, I use Laplace approximation as my computing way to get close the true posterior.<br />
Then I use mean square error as my performance evaluation.<br />
Overall, dirichlet perofmrnace the best among these models( mean square error: 2.74).<br />
It's a significant improvement from the linear model, which only got a 9.7 error.<br />
The earthquake dataset can be found at: https://www.kaggle.com/datasets/grigol1/earthquakes-2000-2023
