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

h1=(w1*i1)+(w2*i2)<br>
h2=(w3*i1)+(w4*i2)<br>
a_h1= σ(h1)=1/{1+exp(-h1)}<br>
a_h2=σ(h2)=1/{1+exp(-h2)}<br>
o1=((w5*a_h1)+(w6*a_h2))<br>
o2=((w7*a_h1)+(w8*a_h2))<br>
a_o1=σ(o1)<br>
a_o2=σ(o2)<br>
E1=½*(t1-a_o1)²<br>
E2=½*(t2-a_o2)²<br>
E_Total=E1+E2<br>


