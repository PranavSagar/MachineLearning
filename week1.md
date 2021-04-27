# Machine Learning
## Logistic Regression
- It is use to predict the possibility of a model  
- We have to provide a set of data to make our model learn .
>This model, which is a very simple model just a linear combination of multiplying the observed data variables by associated parameters just summing them up, mapping that to a variable Zi and then running that through a Sigmoid function. This is a very classic model is called __logistic regression__.   

- <img src="https://github.com/PranavSagar/pic/blob/master/learned_model.png" 
     width="900" 
     height="400" />
- Without data set machine learning wouldn't work
- This is a very simple model with linear predictive model.
- lets assume that there is n numbers of data for every X set  
so we will take single set of Xnth term and multiply each and every term of xnth terms with corresponding parameter and and we will add a additional constant that we called 'bias'.
<img src="https://github.com/PranavSagar/pic/blob/master/Logistic_Regression.png" 
     width="800" 
     height="400" />  


- ### Limitation of logistic regression  
     - Logistic regression can only separate two possible outcome with a linear line which is usefull in certain place but in genral life we doesn't often found distribution is such way, and there can be some curves to seprate two outcomes.s
## Sigmoid Function
- We can use this fuction to predict the possibilities of a certain event to be happen in a model.
- Sigmoid function is a way for us to convert predictions about the outcome of a given model into a probabilistic perspective.
<img src="https://github.com/PranavSagar/pic/blob/master/Sigmoid_Function.png" 
     width="800" 
     height="400" />  

## Multilayer Percepton Concepts  
- In this we are going to do logistic Regression but instead of doing it one time, we are going to do it k times and so now, what we are doing is we are doing effectively k implementations of what we did with logistic regressi9on.
- which are going to map the data x to a k dimensional vector,which is represented by probability from zero to one what we call k latent processes or features associated with the data.
These are called __latent__.

- ### Deep Learning  
     - Deep learning is a form of machine learning where our model is deep in sense that it has multiple layers of latent processes .  
     - Always at top, we have a logistic regression classifier, which is giving us the probabilty of binary output one or zero.
     - Before that we have a lots of intermediate layers .
- So,The key thing to notice is that this model, which is very classic model, which is called multilayer percepton it's also called a neural network,is basically built up by a sequence of repeated application of logistic regression.

- ### Transfer learning 
     - This can be possible in multilayer perceptons that we can transfer the learning to different models.  


>__Convolutional Filter__  
The process by which you shift that atomic element the triangle, to every location in the image that process has a name is called convolutional neural network.  


- Convoltion neural network is a model which can be use for image classification.


