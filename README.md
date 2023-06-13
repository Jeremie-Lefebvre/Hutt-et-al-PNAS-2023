# Hutt-et-al-PNAS-2023

README: Hutt-et-al-PNAS-2023

Results in the manuscript were generated using the custom Python programs contained in this folder. These are notebooks to be used with Google Colab. 

Each code has the similar structure, data structures and generates similarly organized data files. Parameter values used are defined in each code cell independently, or otherwise rely on assignments made in earlier code cells. Different code cells are used to plot different figure panels in each notebook. In all cases, the codes will output graphics files that were collated to be organized using a third party graphics software.

Summary of codes use and output: 

Figure 1A.ipynb: Performs numerical integration of the homogeneous network, plots the output as well as the associated spectrogram

Figure 1B.ipynb: Performs numerical integration of the heterogenous network, plots the output as well as the associated spectrogram

Figure 1CDE.ipynb: Computes statistics of excitability thresholds, plots resulting excitability curves and exemplar response of the network to a pulse like stimulus. 

Figure 2.ipynb: Performs numerical integration of the network for a chosen value of sigma_h (either 0 or 0.05), plots the output as well as representative spike trains,  mean firing rates and effective excitability profiles for the network. Subsequent code cells are performing multi-trial simulations to compute the firing rate correlations. Lastly Lyapunoc explonents along those trials are also computed. Theoretical predictions are also present and plotted alongside the data in each figure. 

Figure 3.ipynb: Computes the spectral radius theoretically as well as the eigenvalue spectra for different values of S_o. Simulations of the network are then performed to compute the spectral radius as a function of time under modulatory perturbations. Lastly the spectral radius is plotted as a function of connexion probability, synaptic weight, network size and response gains. 

Figure 4.ipynb: Theoretical predictions of the spectral radius size as a function of S_o for various degrees of heterogeneity. VAriance of the steady state distribution is also outputted alongside analytical prediction. Network simulations over independent trials are realized to compute the mean transition rate as a function of time and level of heterogeneity. 

Figure 5.ipynb: Theoretical spectral radius heatmap as a function of heterogeneity and modulatory drive amplitude. Susceptibility and resilience metric as a function of heterogeneity. 

Figure 6.ipynb: Performs numerical integration of the network over independent trials for increasing connection probability and synaptic weight and computes the mean Lyapunov exponent in each case.  Heap map of the theoretically calculated spectral radius as afunction of connection probability and synaptic weight. Associated susceptibilty and resilience metric (R_rho, R_mu) as a function of excitability heterogeneity. 

These notebooks generate all the data needed to reproduce all the figures (1-6) from the paper. Name of file specifies which figure/panel it generates.  
 
