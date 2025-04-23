# This File is intended to be used to navigate this independent research project

#### Starting:
I first started with exploring basic probability and expectation theorems which fed into the theory of brownian motion. 

Brownian Motion is considered a random motion based on the Standard normal distribution. 
The exploration of this motion begins with the file called: __Week3BrownianMotion.ipynb__

The file explores the basics of Brownian Motion and what it is supposed to look like. Then we move onto the exploration of Brownian motion in mutliple dimensions to have a feel of what this looks like. The study of Brownian Motion in higher dimensions is located in the file called: __2d brownian motion.ipynb__ 

_Note: 2d exploration was originally tried in the matlab using __Untitled-1.nb__ but proved to be inconvenient after using online resources to expand the scope of the program_.

After learning how Brownian Motion works, the next step was to apply to real world applications like stocks which appear to move randomly. However, the movement of stocks and other assets is not entirely random as they tend to move in a certain direction over time. 

This is modeled with Geometric Brownian Motion. A full exploration of this phenomena is explored in __Modeling Geometric Brownian Motion.ipynb__. The jupyter notebook explores what changes in its parameters looks like for a given asset.

#### Vasicek Model
   
The vasicek model is an application of Geometric Brownian Motion. The first look of the model is located in __Vasicek Model.ipynb__ which explores how the model behaves while also showing examples of the model.

Then we take a small step away from the Model to figure out how to do a regression of the Model which is done in __Least Squares Approximation__ to approximate values for the parameters of the vasicek model over a certain time frame. 

Once I've figured how the regression, I took features from both the Vasicek Model and Least Squares Approximation to test the model's ability in creating accurate predictions. This is located in __Parameter Testing.ipynb__. 

Expanding on the Parameter Testing, what if we found the parameters for the interest rates over a very large period of time? __Long - Term Parameter Testing.ipynb__ answers this question. 


Finally, the current study involves if I could find the parameters using machine learning as the current regressions seem to be unable to fully capture the interest rates