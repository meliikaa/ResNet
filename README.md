# ResNet
🚀 **Residual Networks | Assignment 1 - Week 1**

Welcome! In this README file, I'll introduce you to the fascinating world of Residual Networks (ResNets). 
## Project Overview

In this project, these steps were accomplished:

1. **Implement Basic Building Blocks**: You will dive into the fundamentals of ResNets and implement the essential building blocks of these networks using Keras.

2. **Construct a State-of-the-Art Neural Network**: You'll assemble these building blocks to create and train a state-of-the-art neural network designed for image classification.

3. **Incorporate Skip Connections**: Learn to implement skip connections, a key feature of ResNets that facilitates the training of very deep networks.

## The Power of Depth

Neural networks have evolved from shallow structures to very deep architectures, boasting over a hundred layers. The primary advantage of depth is the ability to represent complex functions and learn features at various levels of abstraction. From detecting simple edges in the shallower layers to capturing intricate features in the deeper layers, depth is a powerful tool.

## The Challenge of Training Depth

However, training very deep networks is not without challenges. One major hurdle is vanishing gradients. In deep networks, gradients can diminish rapidly during backpropagation, leading to slow convergence or even stalling the training process.

As you backpropagate through the layers, each multiplication by the weight matrix can cause the gradient to approach zero exponentially. This phenomenon is known as vanishing gradients and can hinder gradient descent optimization.

## The ResNet Solution

Residual Networks (ResNets), introduced by He et al., address this challenge. ResNets enable the training of exceptionally deep networks by introducing skip connections. These skip connections allow gradient flow from the earlier layers to the later layers, preventing the vanishing gradient problem.


## Conclusion

By the end of this project, you'll have a solid understanding of Residual Networks and their role in training deep neural networks. Dive into the world of deep learning and conquer the challenges of depth with ResNets. If you have any questions or need assistance, don't hesitate to reach out to your instructors or the community. Happy coding! 

## Credits

We owe credit to the Deeplearning.Ai for their invaluable Deep Learning courses on Coursera
![image](https://github.com/meliikaa/ResNet/assets/111120849/90e523ee-9bb1-4113-91bc-53ae0d6266db)
