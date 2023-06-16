## Locally-weighted Logistic Regression  w

  We will implement a Locally weighted version of Logistic Regression, where we weight different
  training examples differently according to the query point.<br>
  Implement the Newton method for optimizing ℓ(θ) for a new query example x based on the
  above calculated gradient and Hessian, and use this to predict the label of x. The initial θ can be set as a
  zero vector.<br>


  The plot_lwlr function visualizes the results of locally-weighted logistic regression (LWLR) on a two-dimensional dataset.<br>
  It creates a grid of points and applies LWLR to each point to make predictions.<br> 
  The function uses a locally_weighted_logistic_regression object to train and predict with LWLR.<br> 
  The resulting predictions are displayed as a color mesh on the grid, where different colors represent different predicted classes.<br> 
  The original data points are also plotted, with their colors indicating the true classes.<br> 
  The function allows for adjusting the parameter tau for LWLR, and it generates a plot to visualize the decision boundary and classification results.<br>
  
![LRWR](https://github.com/im-Shree/Locally-weighted-Log-Reg/assets/90651908/708bc45e-c915-4d37-94dd-12ef20ad8f2a)

Evaluate the model with different bandwidth τ .

  τ = 0.01<br>
![l1](https://github.com/im-Shree/Locally-weighted-Log-Reg/assets/90651908/a52b9e3c-53e2-4b47-9900-45ca59cfdc5a)
  
  τ = 0.1<br>
  ![l2](https://github.com/im-Shree/Locally-weighted-Log-Reg/assets/90651908/f6480fad-6595-4dc7-aa50-d9eec688429f)


Code Reference: https://calvintchi.github.io/classical_machine_learning/2020/08/16/lwlr.html


