mRNA time series data.

GoldingData.mat:
	- panelA1,2,3:	data from three different trials.
		Column 1:	time after induction, minutes
		Column 2:	sample mean of the number of mRNA molecules per bacterium

	- panelC: 
		Column 1: 	log_10 of the sample mean of mRNA count in steady state,
					for various degrees of induction.
		Column 2:	log_10 of the corresponding sample variances of mRNA count

	- panelD1,2,3:	data from three different trials.
		Column 1:	time after induction, minutes
		Column 2:	natural log of fraction of cells with zero copies of mRNA

panelA1.txt etc, panelC.txt, panelD1.txt etc:
	Same data in plain text format.

panelA1.npy etc, panelC.npy, panelD1.npy etc:
	Same data in NumPy array format.

GoldingData.npz:  Same data as GoldingData.mat.

Data from Golding et al. Real-time kinetics of gene activity in individual
bacteria. Cell (2005) vol. 123 (6) pp. 1025--36.
