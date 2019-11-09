# 3D-Bivariate
Generates a 3D bivariate normal distribution with matplotlib trisurf.

Note: this code works for discrete data which is to be modeled _approximately_ as a bivariate normal distribution. Simply use numpy.meshgrid for continuous data.

On the x and y axes, we have the independent variables and the z axis is probability density. The code includes padding with zeros for x-y pairs that do not exist in the dataset.

Coordinates which are padded onto the data will by default have a spacing of one unit, with a z coordinate (probability density) of zero.