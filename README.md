<h2 align="center">Artifical Neural Network From Scratch in Mnist-Digit Dataset.</h2>
<p align="center">
  <img src="https://user-images.githubusercontent.com/40908371/174338354-46e0131d-184b-4768-a036-4b545914334d.png"  alt="Logo" width="300" height="200"/>
  <p>ANN Classifier used to classify MNIST Digit.</p>
</p>

### Concepts/Things implemented in this Notebook:  
  
1. Built Mnisit Digit Classifier with three different layers. (one with 1 layer, 2 layer and 4 layer).  
2. Trained with different optimizers like GD with Momentum, AdaGrad and Adam.  
3. Trained with GPU to boost training.  
P.S.: Everything here is built with numpy, python and pandas."Scratch".  
  
  
### Findings/Results: 
  
  
#### 1. Notebook-1 :  

| Layers | Optimizer | Epoch | Learning Rate| Training Accuracy | Testing Accuracy |
| --- | --- | --- | --- | --- | --- |
| 1 |     Gradient Descent          |  10  | 0.01 | 74.56% | 73.899%
| 2 |     Gradient Descent          |  20  | 0.01 | 89.799% | 88.9111111%
| 4 |     Gradient Descent          |  50  | 0.01 | 74.56% | 73.899%
  
  Note: Since, all the training is done in cpu.  So, while training, go get yourself a cup of coffee.☕😃.  Later we'll try in GPU.😉(Present in the notebook 3)  
   
#### 2. Notebook-2:  

| Layers | Optimizer | Batch Size | Epoch | Learning Rate | Momentum Parmeter | Training Accuracy | Testing Accuracy |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | Mini-Batch Gradient Descent with Momentum | 64 | 50 | 0.01 | 0.9 | 85.232% | 84.649%

#### 3. Notebook-3:  

| Layers | Optimizer | Batch Size | Epoch | Learning Rate | Epsilon | Training Accuracy | Testing Accuracy |
| --- | --- | --- | --- | --- | --- | -- | -- |
| 4 | Mini-Batch Gradient Descent with AdaGrad | 200 | 30 | 0.01 | 10e-8 | 81.085% | __%


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

  
We'll use CNN in this same MNIST DIGIT dataset.   
You can find repo [Here.](https://github.com/shulavkarki/Image-Classification-in-Custom-dataset)
