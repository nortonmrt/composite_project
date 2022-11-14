# Composite structure analysis - Classical Laminate Theory

This project aims to give a basic project analysis for composite structures, using the classical laminate theory. Given the material properties, geometry and the mechanical loads of the structure, the outputs are:

- The stresses and strains in global and local coordinates of each lamina;
- Analysis fo the structure integrity in 3 failure theories: maximum stress, Tsai-Hill and Tsai-Wu;
- Failure graph (as shown in the figure);
- Graphical distribution of stresses and strains along the thickness (also shown in the figures below).

The figures are an example of usage, for a 17-layers laminate. The data from this example is commented on the code.

Failure graph:

![image](https://user-images.githubusercontent.com/108631583/198893378-956a3c4e-3bf9-42a3-9d35-a1d9c963a202.png)

Graphical distribution of stress and strain:

![image](https://user-images.githubusercontent.com/108631583/198893389-3dd93b2f-8934-4909-9f38-6048e7f4adfd.png)
![image](https://user-images.githubusercontent.com/108631583/198893409-909f36fe-20f2-4c19-9e33-d8bed5b55feb.png)

In this first version the laminated properties must be acquired experimentally, but for next versions it will be possible to use theoretical methods such as the Mixture Rule. The user should input the properties, but it is possible also to use the ready example implemented on the code. Just uncomment these data and comment the input functions.

Another feature is that the results of stress and strain can be exported to Excel.

Obs: the author does not take responsibility from the usage of this routine in real engineering projects. The aim of this implementation is purely educational.
