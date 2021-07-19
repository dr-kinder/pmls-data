Image file and filters.

bwCat.tif: A black and white photograph of a cat on a carpet.
864x648 pixels, 8-bit grayscale.

You can import this to MATLAB by using 
	double(imread('bwCat.tif'))
Note the conversion needed to get the image from uint8 type supplied by imread,
to something we can do arithmetic on.

You can import the photo into Python using the PyPlot module:
	plt.imread('bwCat.tif')

bwCat.mat: Same photo as a MATLAB array.

gauss_filter.mat and gauss_filter.csv:
	These files contain a 45x45 array, specifying a Gaussian filter.
