# Resolving Carrier Kinetics in Perovskites through Deep Learning-Assisted Photoluminescence Analysis

Here, we provide the packaged model described in the paper (see the "Packaged_model" folder), which you can use directly. After inputting the joint experimental data of TrPL and PLQY, the model can output the corresponding kinetic parameters. Note that the TRPL data must be within the measurement interval of 0–2 microseconds and the cutoff interval of 0–0.01. In the excel file of "TrPL+PLQY_test.xlsx", we provide some examples of the new data for prediction；

The training code for the final optimized model is provided, see the "Deep_learning_model_traing_code" text；

The training database is provided as the file "TRPL+PLQY.xlsx", which contains the simulated joint TrPL–PLQY profiles and corresponding kinetic parameters used for model development.
