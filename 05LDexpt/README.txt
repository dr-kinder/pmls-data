Luria-Delbruck experiment.

File LDexpt.mat:
	- expcounts23:  data for the experiment in Figs. 4.6 and 4.8.  The data
	  specify a histogram of m with variable-width bins: Bin #i includes
	  outcomes for m in the range bins(i) through (bins(i+1)-1).  The number of
	  cultures with m in this range is expcounts23(i).  Each culture studied had
	  a certain number m of resistant bacteria, out of about 2.4e8 (240 million)
	  bacteria total.

	- expcounts22:  data for another experiment, called #22 (not shown in the
	  text), was similar.  However, in this experiment, each culture was
	  sampled: only 1/4 of the total culture was withdrawn, spread on a plate,
	  and checked for mutants.  Data uses the same bin structure as in
	  experiment #23.  This experiment had about 2.8e8 (280 million) bacteria
	  per culture.

LDexpt23.csv, LDexpt22.csv, LDexpt23.npy and LDexpt22.npy: Same data with bins
in the first column and expcounts in the second column.

LDexpt.npz: Same data as LDexpt.mat

Data from Luria and Delbruck. Mutations of bacteria from virus sensitivity to
virus resistance. Genetics (1943) vol. 28 pp. 491--511, Table 5 (page 505).
