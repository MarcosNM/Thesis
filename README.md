# Predicting Data from Driving profile
I am an Industrial Engineer studying in UPC (Universitat Politénica de Catalunya) and this is my Bachelor thesis.
Thesis is focused on **Hybrid Electric Vehicles**; its main aim is to predict vehicle future velocity. 2 methods have been used:
 * Statistical Methods
 * Neural Networks

### Statistical Methods
Some models like Naive, AR, ARMA have been performed, cotained  in *Statsmodels.ipynb*. Modules needed:
```sh
$ pip install scipy
$ pip install pandas
$ pip install statsmodels
$ pip install scikit-learn
```
### Neural Networks
For time Series Forecasting I choose LSTM model. Some simulations have been done, adjusting parameters to see how each one changes the response. Experiments are included in *NeuralNetworks.ipynb* .Modules needed:
```sh
$ pip install keras 
$ pip install tensorflow
```
*txt.files* contain datasets related with Hybryd Vehicles velocity.
