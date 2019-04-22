---
published: false
---
## Foreword

Recently I had an assignment as part of the deep learning in data science course and I got fascinated by  a simple yet again practical idea that speeds up the learning process with a simple scheduling of the learning rate.


![different optimizer](https://jhui.github.io/assets/dl/a1.gif)

## Role of optimizer and learning rate
Optimization is usually one of the latest stages of a learning process that often is being performed iteratively until the parameters' of interest gets (hopefully) close to what we want. What all these  mean? Let me elaborate.

In a deep learning task we have bunch of data that we feed to a network (model) with a desired target to achieve as an output of the network. In other words, we can see the network as a transformation function that takes some form of data as its input and transforms it to a certain (desired) output of any form. This process is called learning as it "loosely" simulates one. After this stage we can plug the network with expected input to obtain expected output.

One of the elements that helps the learning process and make the transformation successful is the optimizer. It could be thought of as a driver of a car that steers the direction, controls the gas, or stop paddles for the acceleration and even shifting gears for acceleration when necessary. This analogy is actually pretty much what optimizer is all about, but that would be for another blog post. For now let's stay focus on high level understanding or if you already know about all these you can move on more easily.

Another entity worths of mention is the parameter(s) of network also referred to as weights. Optimizer is nothing more than a systematic approach to change the 

## Going cyclical

## What's the right step size?

## What's the right boundary?

## Final word

