# fft_invert
## Fast Fourier transform weak lensing mass reconstruction
    
The code implements the technique described in [Lombardi & Bertin (1999)](https://ui.adsabs.harvard.edu/abs/1999A%26A...348...38L/abstract)
to invert weak lensing measurements into the dimensionless mass density, taking into account
the noise and the finite-field effects.

The procedure is contained within the notebook: to use it, one has just to copy the second
cell, containing the necessary includes and the definition of `fft_invert`, which
actually performs the inversion.

In case you use this code, kindly cite the original paper mentioned above.
