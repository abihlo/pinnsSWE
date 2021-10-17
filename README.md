# Physics-informed neural networks for solving the shallow water equations on the sphere

*Accompanying code for the paper "Physics-informed neural networks for the shallow-water equations on the sphere" by A. Bihlo and R.O. Popovych, https://arxiv.org/abs/2104.00615.* 

We propose to use a variation of physics-informed neural networks to solve the shallow-water equations on the rotating sphere. The shallow-water equations are the canonical test bed for developing novel algorithms for the dynamical core of weather and climate prediction models. Here we show that a neural network based algorithm can produce accurate solutions to the shallow-water equations in latitude-longitude coordinates.

In our paper we present 4 different canonical test cases for the shallow-water equations on a rotating sphere, originally proposed by Williamson et al. [J. Comput. Phys. 102, 211-224, 1992]. These test cases are:

1) Advection of a cosine bell around the sphere
2) Nonlinear geostrophic flow on a sphere
3) Flow over a conically shaped mountain
4) Rossby-Haurwitz wave solution

Codes are provided for all four test cases. Note that test case 1 is peculiar in that a linear advection equation is solved instead of the full nonlinear shallow-water equations. Test cases 2-4 use essentially the same code for solving the shallow-water equations, with the difference being in the hyperparameters choses as well as in the visualization part of the routine.

The codes have been written in TensorFlow 2.4 and ran on Google Colab.
