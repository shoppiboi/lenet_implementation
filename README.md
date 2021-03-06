# LeNet Implementation (Python)

## About

An OOP implementation of the LeNet CNN architecture. 
I made this to further build upon the basics I learned after working through the book *Make Your Own Neural Network* by Tariq Rashid.
I decided to go for a more "vanilla" implementation to get a better understanding of what is happening "under the hood".

**Libraries used:**
* [NumPy](https://numpy.org/) (1.19.3)

**Resources used:**
* [*Make Your Own Neural Network*, Tariq Rashid](https://www.amazon.co.uk/Make-Your-Own-Neural-Network-ebook/dp/B01EER4Z4G)
* [*CS231n Convolutional Neural Networks for Visual Recognition*, Stanford](https://cs231n.github.io/convolutional-networks/)
* [*Backpropagation in Convolutional Neural Networks*, Jefkine](https://www.jefkine.com/general/2016/09/05/backpropagation-in-convolutional-neural-networks/)

## Results:

### Fully Connected Network
    +-------------------------+
    | Fully Connected Network |
    +-------------------------+
    Learning Rate: 0.1
    Input Shape: (784,)
    +-----------------------+--------------+
    | Layer Type            | Output Shape |
    +-----------------------+--------------+
    | Fully Connected Layer | (200,)       |
    | Activation (Sigmoid)  | (200,)       |
    | Fully Connected Layer | (10,)        |
    | Activation (Sigmoid)  | (10,)        |
    +----------------------+---------------+
    
    Accuracy: 0.9732
