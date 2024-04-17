# active-learning-for-biochar-design
An active learning model employing RF regressor and PSO optimizer to recommend experimental conditions aimed at designing property specific biochar

A full dataset titled "Data for model" which includes all the experimental data used for model training is attached as an excel file. The file itself contains 4 tabs, with each tab corresponding to the experimental data from each of the active learning cycles.

The jupyter notebook "RF and PSO model.ipynb" attached can be run directly after all the relevant libraries are installed. It uses the data from the excel sheet to train the model and makes its predictions on the optimal set of experiments to be performed in the subsequent active learning cycle.


#If you find this work relevant, please cite our published paper:

Active learning based guided synthesis of engineered biochar for CO2 capture
X. Yuan, M. Suvarna, J.Y. Lim, J. Pérez-Ramírez, X. Wang, Y.S. Ok
Environ. Sci. Technol. 2024, 15, 6628–6636. (https://pubs.acs.org/doi/10.1021/acs.est.3c10922)
