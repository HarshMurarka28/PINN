PINN is basically a neural network used to solve complex PDEs which are hard to solve with traditional method
For this we cant use our standard neural networks because standard neural networks require a very large amount of data to work well but producing data is very costly in physics so instead we use our already known
knowledge in physics
So we use PINN which instead of just reducing loss on predicted values, it also forces it to satisfy know physics which makes it converge very fast
So to solve any physical problem we will just need 2 things : 1) Its PDE
                                                              2) Its boundary conditions
