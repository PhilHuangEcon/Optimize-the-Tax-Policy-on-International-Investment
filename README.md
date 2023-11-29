# Optimize-the-Tax-Policy-on-International-Investment
All codes listed here are solo work and require proprietary data. This document gives a brief introduction to the purpose of each program file. For more information, please contact me through email.
1. 1.MeasureBunching.ipynb: Built a model to measure firms’ bunching behavior faced with the tax policy, leveraging the multilinear regression. This file also conducted the model evaluation and selection using K-fold cross-validation, and non-parametric hypothesis testing using the bootstrapping method.
2. 2.Draw_bunching_graph.ipynb: Visualized results from the previous step.
3. 3.bootstrap_bunching.ipynb: Resampled using bootstrapping and constructed matrix of the data moments.
4. 4.calibration.ipynb: Used Simulated Moment Method to calibrate the parameters and conducted hypothesis testing using bootstrapping.
5. 5.simulate_cross_section.ipynb: Visulized firms’ decision-making predicted by the model with the tuned parameters.
6. 6.Counterfactual_change_Parameters.ipynband7.Counterfactuals_Decomposition.ipynb: Conducted counterfactual analysis with the tuned model.
