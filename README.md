Solving Differential Equation Synchronously
========================================================================


Evolved from [this artificial neural network algrimth](https://github.com/NeuPhysics/aNN). Regarding the generality of this method, a new repo is created here.

By synchronously we mean the solution to the differential equation will be obtained at the same time for each value of the argument.

I learned the artificial neural network method from Shashank who is the postdoc in our group. And this is derived directly from that ANN method I learned. The reason I think this is important is that the method is so beautiful and intuitive. Nonethless I realized this is not efficient.

The basic idea is to solve the equation without doing step by step integration numerically instead we find a proper parameterization and then find the parameters for the specific equation and initial condition or boundary condition.

By proper parameterization, I mean a good approximator. In the theory of Artificial Neural Network, sigmoid is a good universal approximator. Now I am telling myself, universal is not required for a specific proble as long as one can find a better parameterizatioin for the specific problem. This is an idea from Kolmogorov's theorem.

In fact even with a bad parameterization, the method will also work as long as enough dimension of the parameters is provided.





