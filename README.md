# ANN-Scratch-In-MnsitDigit
MNIST Digit image classifier built using Artificial Neural Network from Scratch with python and numpy.  
  
### Considerations:    
1. OPTIMIZER : Gradient Descent  || Mini-Batch Gradient Descent with Momentum || Mini-Batch GD with ADAGrad
2. LEARNING RATE : 0.01  
3. Epoch : 50 (Accuracy will boost on higher epochs.)
  
#### Three ANN of different layers is used to classify images.

1. One Hidden Layer 
  ![image](https://user-images.githubusercontent.com/40908371/173662434-a87069c7-049c-43be-959f-46b8a26986e5.png)
  
  Results:  
  Training Accuracy: 74.67%   
  Testing Accuracy: 75.21%    
  
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------  
    
2. Two Hidden Layer
 ![image](https://user-images.githubusercontent.com/40908371/173663019-e7d25df7-4111-4816-b694-cabe61d0f1a1.png)
     
  Results:  
  Training Accuracy: 89.34% 
  Testing Accuracy: 88.9932%    
   
   --------------------------------------------------------------------------------------------------------------------------------------------------------------------  
     
3. Four Hidden Layer
![image](https://user-images.githubusercontent.com/40908371/173862561-57e26da0-49dd-4437-ad12-9440ceaea7c4.png)
  
  
  Results:  
  Training Accuracy:  
  Testing Accuracy:   
  
   -------------------------------------------------------------------------------------------------------------------------------------------------------------------- 
   --------------------------------------------------------------------------------------------------------------------------------------------------------------------  
   

  
Note: In this notebook, i've trained only for few epochs. Since i'm using cpu to train my model, it is going to take time(a lot in more layers ANN).  
      So, if you want to get boost in the accuracy, train the model in more epochs. 
