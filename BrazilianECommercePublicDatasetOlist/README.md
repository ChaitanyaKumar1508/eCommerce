# Session-3

In this project we had to use less than 20k params in our network to reach the accuracy of more than 99.4% on MNIST dataset, using keras

![keras](https://miro.medium.com/max/1200/1*c40CcKNMg2xHMG6CuKXv7Q.jpeg)



MINST dataset :

![MINST dataset](https://miro.medium.com/max/1400/1*XdCMCaHPt-pqtEibUfAnNw.png)





- We have designed the network in such a way that it reached the accuracy of 99.27% with around 19k params.

- We played around with the number of kernels to achieve this, and using max pooling just once.


![The Max-Pooling](https://mlblr.com/images/maxpool.gif)



- During our experiment we tried with various network designs (without using DropOut or BN or LR), with few involving 2 times max pooling, but this one was the best model out of all those.

