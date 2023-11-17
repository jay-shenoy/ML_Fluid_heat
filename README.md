# ML_Fluid_heat
My journey in mastering AI/ML applied to numerical experiments/simulations

I took break from my learning path of using AI/ML tools in fluid dynamics
Restarting again in my PhD journey.

From where does data come ?
If Simulation/Numerical experiments could be LBM , traditional CFD , SPH , FEM  it is called PINNS
If experiments gives you data EINNS.

Simulation takes lot of time(computational time) so run on coarse mesh(less # of grid points) which less computationally expensive , later feed that data to train the neural network which is supervised learning for you.
Obviously you need lot of data to train the network later you can use test data to see if prediction by NN matches well.
In summary it is approximating function/interpolation/curve fitting.

Neural network avoids meshing which is cumbersome in CFD.

Next question , can we incorporate physics into the data(bring some equation) which is PINNS(Physics Informed Neural Networks)

Later do inverse problems with NN (since NN are inherently inverse problems since it is all about finding optimal weights with forward pass & back propogation i.e adjusting)

We start always with 1D which can be easily understood by anyone.
