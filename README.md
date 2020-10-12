# OpenNAS_v1
A system integrating open source tools for Neural Architecture Search (OpenNAS), in the classification of images, 
has been developed. OpenNAS takes any dataset of grayscale, or RBG im- ages, and generates Convolutional Neural Network 
(CNN) architectures based on a range of metaheuristics using either an AutoKeras, a transfer learning or a Swarm Intelligence (SI) approach.

Particle Swarm Optimization (PSO) and Ant Colony Optimization (ACO) are used as the SI algorithms. Furthermore, models 
developed through such metaheuristics may be combined using stacking ensembles.

## Table of contents
* [General info](#general-info) <!---* [Screenshots](#screenshots) -->
* [Technologies](#technologies) <!---* * [Setup](#setup) -->
* [Inspiration](#inspiration)
* [Contact](#contact)

<!---* ## General info
Add more general information about project. What the purpose of the project is? Motivation? -->

!## Screenshots
![Example screenshot](./img/screenshot.png)

## Technologies
* Python 3.7
* Tensorflow 1.14
* Keras 2.2.4
* Numpy 1.16.4
* Matplotplib 3.1.0.

## Inspiration

Byla, E. and Pang, W., 2019, September. Deepswarm: Optimising convolutional neural networks using swarm intelligence. In UK Workshop on Computational Intelligence (pp. 119-130). Springer, Cham.

Junior, F.E.F. and Yen, G.G., 2019. Particle swarm optimization of deep neural
networks architectures for image classification. Swarm and Evolutionary Compu-
tation, 49, pp.62-74.

DeepSwarm library: 
Copyright (c) 2019 Edvinas Byla

pso-CNN:[particle.py, population.py, pso-CNN.py, utils.py] 
Copyright (c) 2020 Francisco Erivaldo Fernandes Junior

## Contact
Created by [@seamuslankford] - feel free to contact me!
