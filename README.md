# Intro to pytorch

Material in this repository is inspired by ... and partly taken from ...

As you already know, python has libraries for nearly all tasks. For machine learning, the two most popular ones are pytorch and tensorflow. Even though tensorflow may be a little easier to start with, pytorch offers more flexibility, which is why we like to work with it.

### Tensors

THE data structure in machine learning is the so-called Tensor.
It is a structure that is very similar to numpy arrays, but they can be used on GPUs. And GPUs we really need if we don't want to get old waiting ...

You can create tensors from: numpy arrays, ...

A tensor has 3 attributes:
- shape
- data type
- device
these words you will often see in error messages, because pytorch complains about shapes not matching, and data types and devices not being the same.

One of the most important thins (in my opinion) are tensor operations and "views".
Operations should look pretty familiar, since they are very similar to those in numpy. If you want to browse all what pytorch has to offer or need more details about something, go to the documentation https://pytorch.org/tutorials/.

### Modules

The next big new thing in pytorch are modules. These are actually what makes machine learning so easy nowadays (wink).
What is a module? what defines it/what are its characteristics?

### Datasets and DataLoaders

### Neural Networks in Pytorch

How do I write a neural network class in pytorch?
Important: init and forward

### Loss functions

### Optimizers

### How to train a neural network - simplified

#####################

need to explain:
- Tensors
    - a new data structure to learn
    - luckally THE data structure to learn
    - view, reshape, ... those things with tensors
- Modules
    - why do they need the forward function, what is it?
    - how is stuff trained behind the scenes? (maybe...) -> where are the parameters
    - demonstrate backprob on a simple tensor computation (the magic of pytorch, automatic differentiation)

we should also have a small section in the course about "when does ML make sense?" -> Cover's theorem
