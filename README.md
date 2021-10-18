# Genetic_Algorithm
Genetic Algorithm made in Python to estimate a Weierstrass function

## Subject
Astronomers have observed a new, unknown star. Their first observations let us believe that the temperature on its surface varies regularly with several periodicities such as
shown below.
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/60/WeierstrassFunction.svg" width="300px" >
</p>

Astronomers assume that the star follows a Weierstrass function with several nested periodicities in the fractal sense, that we define as :
<p align="center">
  <img src="https://user-images.githubusercontent.com/92330168/137647308-af916919-92c6-4d07-8df6-e744bdd474f1.png" width="200px" >
</p>
 With  t(i) the temperature of the star at a given instant i and with the set of parameters:
 <p align="center">
  <img src="https://user-images.githubusercontent.com/92330168/137647356-83c67168-9e91-4e29-99d4-5c6cffc42542.png" width="200px" >
</p>

The goal is to determine the combination (a, b, c) capable of bringing the Weierstrass function closer to the temperature observations made at given times. A list
of observations was provided as our dataset. It's a search problem and we decide to implement a genetic algorithm to solve it.


## Understanding the Algorithm 

The genetic algorithm is a method inspired by the process of natural selection that belongs to the larger class of evolutionary algorithms. It is divided into three main parts.

1) Evaluation of all our individuals using the difference between our predicted values and the actual values
2) Selection of the best individuals + crossing/mutation + random individuals to avoid eugenism.
3) Loop it until we surpass our precision threshold 

![image](https://user-images.githubusercontent.com/51094403/136415070-f71272c2-4de9-444d-931d-1978a32f234a.png)

# Note
The python code and the report are in French but do not hesitate to contact me if you want more details in English.
