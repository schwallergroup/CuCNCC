# CuCNCC

Complementary code to the project titled _Exploring the potential of machine learning as a tool for chemical synthesis using SHAP_ done in the context of a summer internship in EPFL's LIAC and supported by the Laidlaw Foundation.

This contains chronologically ordered notebooks which analyse and use the data set from the paper _Bayesian Optimization as a Sustainable Strategy for Early-Stage Process Development? A Case Study of Cu-Catalyzed C–N Coupling of Sterically Hindered Pyrazines_ by Braconi E. and Godineau E. (doi: 10.1021/acssuschemeng.3c02455) to train select machine learning models. Later on, by using the python shap package, these trained machine learning models are investigated in order to comprehend why they are or are not performant.

The goal was to see if more simple machine learning models (RandomForestRegressor, XGBoost, GAM, LinearRegressor...) were capable of accurately predicting the yield of a specific reaction depending on its features after being trained with a data set involving real-life experiments. Furthermore, by picking the most performant model we pushed the analysis with SHAP further to see if we could use it to propose new reaction with potentially high yields. Additionally certain functions were written to have natural language explanations from the numerical outputs provided by the shap package.

_This repository is still being updated, so the code is not optimal at the moment._
