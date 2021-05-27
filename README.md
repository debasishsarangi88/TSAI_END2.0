TSAI_END2.0 <br>
This Repository is for the TSAI END2.0 session 4 task. <br>


Debasish EVA P2S3 file has activation functions defined as mentioned below

def sigmoid(x): # sigmoid function
  return 1/(1+np.exp(-x))

def dsigmoid(y): # derivative of sigmoid function
  return y * (1 - y)

def tanh(x): # tanh function
  return np.tanh(x)

def dtanh(y): # derivative of tanh
  return 1 - (y * y)
  
  All the answer to the questions are also mentioned on the colab notebook.
  
  Following is error vs epoch graph after running the model for 50000 epochs.
  
  ![image](https://user-images.githubusercontent.com/39134120/119880759-31dd3d80-bf4a-11eb-8ba5-69d060ec10ab.png)


