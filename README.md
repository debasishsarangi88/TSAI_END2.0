# TSAI_END2.0
This Repository is for the TSAI END2.0 Session2 task.

This readme file explains the one of the coolest assignments i.e. showing forward and backward pass of a small Neural network in MS Excel.

![Network Structure](https://user-images.githubusercontent.com/39134120/118083756-16682380-b3dd-11eb-937e-56117f5ded97.JPG)

The above image shows the architecture of the Neural network.<br>
We have considered a samller network with less layers as we are doing the entire excercise in MS Excel.<br>
i1 and i2 are the input layer neurons.<br>
h1 and h2 are the hidden layer neurons.<br>
a_h1 and a_h2 are activated outputs from hidden layer neuron h1 and h2.<br>
o1 and o2 are the neuron connected to the output layer.<br>
a_o1 and a_o2 are activated output of o1 and o2 neuron.<br>
E_total is the output of the network.<br>
w1 and w3 are the weights from input layer neuron i1 to h1 and h2 respectively.<br>
w2 and w4 are the weights from input layer neuron i2 to h1 and h2 respectively.<br>
w5 and w7 are the weights from activated hidden layer neuron a_h1 to o1 and o2 respectively.<br>
w6 and w8 are the weights from activated hidden layer neuron a_h2 to o1 and o2 respectively.<br>

Follwing are the values calculated for different parameters of the above shown Neural network.

![parameter_values](https://user-images.githubusercontent.com/39134120/118086285-53ceb000-b3e1-11eb-81f0-cbdca8630a7e.JPG)

We know that the chain rule is used for calculating the derivative of composite functions. If a variable z depends on the variable y, which itself depends on the variable x, so that y and z are dependent variables, then z, via the intermediate variable of y, depends on x as well. This is called the chain rule.Just like this the input/hidden layer neuron has impact on the final output obtained in the final layer.The weights associated with the input/hidden layer is optimized via their association with the output layer which itself updated via loss calculated from difference between predicted and actual value.

So using above concept when we calculated values for different parameters we got the following.

![Weight_calc1](https://user-images.githubusercontent.com/39134120/118123847-70371080-b412-11eb-845d-3eb86bb9555d.JPG)
![Weight_calc2](https://user-images.githubusercontent.com/39134120/118123881-79c07880-b412-11eb-8126-b233d1d70596.JPG)
![Weight_calc3](https://user-images.githubusercontent.com/39134120/118123906-804ef000-b412-11eb-91e1-61adcdb872ed.JPG)
![Weight_calc4](https://user-images.githubusercontent.com/39134120/118123929-8644d100-b412-11eb-9847-e6c8b4b9a8db.JPG)
