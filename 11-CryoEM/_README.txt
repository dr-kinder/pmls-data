cryoEM simulated data

1dImages.npz: contains variables:
noiselevels = array containing 1/sqrt(SNR) for each of 3 simulated datasets
shiftSD = how many pixels to jitter the fake data
samples = 3D array containing simulated images
	samples[i,j,k] where i=which image, j = position in image, k = which noiselevel

2dImages.npz: contains variables:
noiselevels = array containing 1/sqrt(SNR) for each of 3 simulated datasets
shiftSD = how many pixels to jitter the fake data
samples = 4D array containing simulated images
  samples[i, jx, jy, k] where i=which image, j = position in image, k = which noiselevel

test2Dblur.tif contains a 2d image, 85x85 pixels, to be used as an initial target for refinement.

