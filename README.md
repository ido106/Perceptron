# The Perceptron Algorithm - Machine Learning
## Introduction
In this exercise we will touch the world of [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning).  
Machine learning is a branch of [Artificial Intelligence (AI)](https://en.wikipedia.org/wiki/Artificial_intelligence) and computer science which focuses on the use of data and algorithms to imitate the way that humans learn, gradually improving its accuracy.  

In particular, we will implement the [Perceptron algorithm](https://en.wikipedia.org/wiki/Perceptron).  
A perceptron is a Machine Learning type computer program that can learn how to make decisions based on some data. The Perceptron takes information about some data and then use that information to make decisions.  
Before trying to understand the algorithm, I suggest reading about the Perceptron first.

**Let's give an example:**  
Suppose we want to teach the perceptron how to tell the difference between a car and a motorcycle.  
First, we will probably show it a lot of images of cars and motorcycles and tell it what each image is.  
The perceptron would look at the tagged images we provided, and try to find the differences between a motorcycle and a car. It is likely that It will first notice that a motorcycle has two wheels and a car has four wheels, that the motorcycle is a small, open vehicle compared to the car, and so on.  
After it has learned many examples, the perceptron should begin to recognize patterns and make decisions on its own whether a new image is a car or a motorcycle. If the perceptron makes a prediction error, we will tell it the right answer and help it correct itself to improve accuracy on the next attempt.

Perceptrons can be used for many purposes, and this algorithm is used in many technologies we use today.
<p align="center">
  <img 
    width="500"
    src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8a/Perceptron_example.svg/750px-Perceptron_example.svg.png"
  >
</p>

## Running Instructions
In the ML tasks, and in particular in this task, we will use [Google Colab](https://colab.research.google.com/) to run the code in an iterative and convenient way.  
To preview the notebook, you can click on `Perceptron.ipynb` in this repository.  
In the notebook you can find a detailed explanation about the algorithm and the code step by step.  
To run the code, first clone the repository to your computer with `git clone https://github.com/ido106/Perceptron.git`, then drag the notebook (`Perceptron.ipynb`) and the dataset (`dataset.csv`) to your [Google Drive](https://www.google.com/drive/).  

**Enjoy !**
