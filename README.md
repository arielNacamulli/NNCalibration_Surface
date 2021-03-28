# NN Surface Calibration
## _A Neural Network method of implied volatility_

### Main Notebooks
The repository includes script and function to solve implied volatility calibration problem using NN. The method is implemented and tested in Jupyter notebooks starting with "NN Surface Calibration". 5 models are implemented:
- rBergomi
- 1-Factor Bergomi
- Heston
- VGSSD
- NIGSSD

For first two models are considered two different modelling of forward variance curve.

Part of the dataset is taken from [here](https://github.com/amuguruza/NN-StochVol-Calibrations/tree/master/Data), and is relative to this [paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3322085).

The rest of the dataset is built via the "DataSet Creator.ipynb" notebook.

### Other Notebooks

Other notebooks are devoted to a test on the NN architecture ("Neural Network Layer Test.ipynb") and the implementation and testing of another NN with the aim of predicting the best fitting model ("Category NN" notebooks)