Myosin stepping data.

File g42myosinwalk.mat contains these variables:
	- yildizHistoRed: stepping histogram for myosins taking only 70nm steps;
	- yildizHistoGreen: stepping histogram for myosins taking (70-x)nm steps
	  alternating with x nm steps.

In each case, each row consists of a pair:
	(center of histogram bar in seconds, observed frequency)

redDelta=0.5, greenDelta=1: respective bin widths in seconds.

Files yildizHistoRed.csv, yildizHistoGreen.csv, yildizHistoRed.npy, and
yildizHistoGreen.npy, contain the same information.

g42myosinwalk.npz: Same data as g42myosinwalk.mat.

Data from Yildiz et al. Myosin V walks hand-over-hand:
	Single fluorophore imaging with 1.5-nm localization.
	Science (2003) vol. 300 (5628) pp. 2061, Fig. 6.
