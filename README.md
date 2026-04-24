# Resolving Carrier Kinetics in Perovskites through Deep Learning-Assisted Photoluminescence Analysis
Here, we provide the packaged model described in the paper (see the "Packaged_model" folder), which you can use directly. After inputting the joint experimental data of TrPL and PLQY, the model can output the corresponding kinetic parameters. Note that the TRPL data must be within the measurement interval of 0–2 microseconds and the cutoff interval of 0–0.01；
The training code for the final optimized model is provided, see the "Deep_learning_model_traing_code" text；
Here, we provide the packaged model described in the paper (see the "Packaged_model" folder), which you can use directly. After inputting the joint experimental data of TrPL and PLQY, the model can output the corresponding kinetic parameters. Note that the TRPL data must be within the measurement interval of 0–2 microseconds and the cutoff interval of 0–0.01. The studied cases in the paper are also provided.

The training code for the final optimized model is provided, see the text "Deep_learning_model_traing_code".

The training database is provided as the file TRPL+PLQY.csv, which contains the simulated joint TrPL–PLQY profiles and corresponding kinetic parameters used for model development.
