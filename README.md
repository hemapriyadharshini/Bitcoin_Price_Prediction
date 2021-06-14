# Bitcoin Price Prediction
# Steps:
1) Import Package
2) Import Data
3) Pass data to prophet object and fit model
4) Extend historical data values to future dates
5) Predict future price
6) Plot prediction and seasonality chart
7) Save output data to csv file

# Notes:
- Latest python version does not support FBProphet package. In order to overcome this challenge, following steps are executed
    1) Create a new virtual environment
    2) Install Python 3.7 version
    3) Install [MinGW](https://sourceforge.net/projects/mingw/) C++ Complier
    4) Install Pre-requisite packages (Cythan, Pystan,etc.,)
    5) Install FBProphet 
        
        conda create -n py3.7 python=3.7
        
        conda activate py3.7
        
        conda install -c conda-forge fbprophet

- Used anaconda command prompt for the first time. It's easy to use and operate like Shell Scripting
