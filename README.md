# ANN-Scratch-In-MnsitDigit
MNIST Digit image classifier built using Artificial Neural Network from Scratch with python and numpy.  
  
### Considerations: 
  
  
#### 1. Notebook-1 :  

| Layers | Optimizer | Epoch | Learning Rate| Training Accuracy | Testing Accuracy |
| --- | --- | --- | --- | --- | --- |
| 1 | Gradient Descent | 10 | 0.01 | 74.56% | 73.899%
| 2 | Gradient Descent | 20 | 0.01 | 89.799% | 88.9111111%
| 4 | Gradient Descent | 50 | 0.01 | 74.56% | 73.899%


  Layers : 1 , 2 and 4 ( MNIST Digit Image is trained in 3 different layers one with 1 Hidden Layer other with 2 and 4 Hidden layer. )  
  OPTIMIZER : Gradient Descent  
  LEARNING RATE : 0.01  
  Epoch : 50 (Accuracy will boost on higher epochs.)
  
  Note: Since, all the training is done in cpu.  So, until then, go get a cup of coffee.☕😃. Later we'll try in GPU.😉  
  
    
#### 2. Notebook-2:  
  Layers : 2 ( MNIST Digit Image is trained with 2 Hidden Layer)  
  OPTIMIZER : Mini-Batch Gradient Descent with Momentum 
  LEARNING RATE : 0.01  
  Epoch : 50 (Accuracy will boost on higher epochs.)
  
  Note: Since, all the training is done in cpu.  So, until then, go get a cup of coffee.☕😃. Later we'll try in GPU.😉

  
#### Three ANN of different layers is used to classify images.

1. One Hidden Layer 
  
    
  ![image](https://user-images.githubusercontent.com/40908371/173662434-a87069c7-049c-43be-959f-46b8a26986e5.png)
  

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------  
    
2. Two Hidden Layer

  
 ![image](https://user-images.githubusercontent.com/40908371/173663019-e7d25df7-4111-4816-b694-cabe61d0f1a1.png)
     

   
   --------------------------------------------------------------------------------------------------------------------------------------------------------------------  
     
3. Four Hidden Layer
  
    
![image](https://user-images.githubusercontent.com/40908371/173862561-57e26da0-49dd-4437-ad12-9440ceaea7c4.png)
  
  

   -------------------------------------------------------------------------------------------------------------------------------------------------------------------- 
   --------------------------------------------------------------------------------------------------------------------------------------------------------------------  
   

  
Note : In this notebook, i've trained the model only for few epochs. Since i'm using cpu to train the model, it is going to take time(a lot in more layers ANN).
So, if you want to get boost in the accuracy, train the model in more epochs. 
