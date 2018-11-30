# WassersteinRobustSummarization
In this public repository you can find and implementation of the Wasserstein Robust nuclear norm summarization algorithm using ADMM.

The theory behind the method can be found on the paper "Graph clustering and the nuclear Wasserstein metric." by de Roux and Velasco to be 
soon avainble in ArXiv.

Three jupyter notebooks containing the code in Julia are available.

AuxFunctions.ipynb containts auxiliary functions necessary to run the other scripts.

admmRecovery.ipynb contains the main algorithm to solve the Wasserstein Robust nuclear norm summarization problem. It is a form of 
global consensus with regularization.

GraphLearning.ipynb contains the implementation of the Wasserstein robust summarization using other norms and the nuclear norm. The key difference is that all these algorithms call Mosek, an off the shelf numeric solver. In order to run them, the user need to have a valid Mosek licence (which is available in their website for free for academic purposes).
