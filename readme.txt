# Sample of 10000 GalSim simulated galaxy images from Great3
# Each image has 41x41 pixels and is sampled at twice Euclid resolution and normalised by the sum of pixel values
#
# This tarball contains two files:
#
# - galaxy_cube_10000.npy which is a Numpy binary file that can be read using the following command:
# 
# >>> import numpy as np
# >>> np.load(‘galaxy_cube_10000.npy’)
# 
# - galaxy_cube_10000.fits which is a FITS binary file that can be read into Python using package like Astropy as follows:
# 
# >>> from astropy.io import fits
# >>> fits.getdata(‘galaxy_cube_10000.fits’)
#
# checkout http://www.cosmostat.org/software/sf_deconvolve for more details
