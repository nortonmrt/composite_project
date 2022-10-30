# Composite structure analysis - Classical Laminate Theory

This project aims to give a basic project analysis for composite structures, using the classical laminate theory. Given the material properties, geometry and the mechanical loads of the structure, the outputs are:

- The stresses and strains in global and local coordinates of each lamina;
- Analysis fo the structure integrity in 3 failure theories: maximum stress, Tsai-Hill and Tsai-Wu;
- Failure graph (as shown in the figure);
- Graphical distribution of stresses and strains along the thickness (also shown in the following figures).

Failure graph:
![image](https://user-images.githubusercontent.com/108631583/198893050-f5786829-e904-45e5-a901-f012f42a3e49.png)

Graphical distribution of stress and strain:
![image](https://user-images.githubusercontent.com/108631583/198893199-ced11214-fb50-441c-8c04-9b7ec727e723.png)
![image](https://user-images.githubusercontent.com/108631583/198893247-13c63cc2-786b-4983-8abd-37d80ebfacf2.png)

In this first version the laminated properties must be acquired experimentally, but for next versions it will be possible to use theoretical methods such as the Mixture Rule. The user should input the properties, but is possible also to use a ready example implemented on the code. Just uncomment these data and comment the input functions.

Another feature is that the results can be exported to Excel.

The author does not take responsibility from the usage of this routine in real engineering projects. The aim of this implementation is purely educational.
