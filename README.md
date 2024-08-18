# Binary-Classification-using-Logistic-Regression

Training the logistic regression model

Learning Rate and Stop Criteria Discussions:

We're using sklearn's LogisticRegression, which uses 'lbfgs' solver by default.
This solver doesn't use a fixed learning rate, but adapts it during optimization.
The stop criteria is controlled by 'tol' and 'max_iter' parameters.
Learning Rate Settings:

As mentioned, 'lbfgs' solver adapts the learning rate automatically.
We can control the convergence with 'tol' parameter, set to 1e-4 by default.
Stop Criteria Settings:

max_iter: Maximum number of iterations, set to 1000
tol: Tolerance for stopping criteria, set to 1e-4
Parameters Obtaining Discussions:

The model learns the coefficients (weights) for each feature.
It also learns an intercept term.
The optimization process minimizes the log-loss function.
