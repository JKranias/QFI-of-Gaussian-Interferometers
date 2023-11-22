# QFI-of-Gaussian-Interferometers
A collection of code used to compute and optimize the quantum Fisher information (QFI) of lossy Gaussian interferometers with coherent seeding. 
This code was made while researching and writing a paper on Nonlinear Interferometry

# (C) Copyright Jasper Kranias, 2023.
#
# This code is licensed under the Apache License, Version 2.0. You may
# obtain a copy of this license in the LICENSE.txt file in the root directory
# of this source tree or at http://www.apache.org/licenses/LICENSE-2.0.
#
# Any modifications or derivative works of this code must retain this
# copyright notice, and modified files need to carry a notice indicating
# that they have been altered from the originals.


QFI Calculations.nb is a Mathematica notebook which can compute analytic expressions for the QFI of a losy Gaussian interferometer with coherent state seeding.
The schemes used are Mach-Zehnder, Yurke, and Mandel, but you can use the Gaussian operations defined in the code to construct your own schemes or include loss in different places.

Mandel All Modes Calculation.nb shows an example of computing the QFI where there are some problems with the calculation and you have to do some parts manually.

Gaussian QFI Optimization.ipynb is a jupyter notebook where I numerically optimized the QFI and generated plots used in the paper.
