# ML_Fluid_heat
My journey in mastering AI/ML applied to flows(isothermal , non-isothermal)

I took break from my learning path of using AI/ML tools in fluid dynamics , heat transfer.
Restarting again in my PhD journey.

From where does data come ?
Simulation/Numerical experiments could be LBM , traditional CFD , SPH , FEM etc

Simulation takes lot of time(computational time) so run on coarse mesh(less # of grid points) which less computationally expensive , later feed that data to neural network which is supervised learning for you.
Obviously you need lot of data to train the network later you can use test data to see if prediction by NN matches well.

Neural network avoids meshing which is cumbersome in CFD.

Next question , can we incorporate physics into the data which is PINNS

Later do inverse problems with NN

We start always with 1D which can be easily understood by anyone
