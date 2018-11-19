# Fisher discriminant-based data point cloud separability analysis

This github implements the methodology of separability analysis of data point clouds described in [Gorban A,N. et al, Correction of AI systems by linear discriminants: probabilistic foundations. 2018. Information Sciences 466:303-322.](https://www.sciencedirect.com/science/article/pii/S0020025518305607)

The method implemented allows a) quantifying the effective data dimension based on comparing the separability distributions with a uniformly sampled n-dimensional sphere, and b) quantify the empirical probability distribution of a data point to be separated from the rest of the data point cloud.

## MATLAB implementation (provided by A.Zinovyev)

In order to test the code, execute

	addpath tests;
	testSeparabilityAnalysis;



