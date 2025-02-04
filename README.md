# IFU
The code is divided into two main folders:
    "Task12": containing two files both combining tasks 1 and 2 of the project—data cleaning, predictive model choice and construction of the three cost matrices (distance, time and financial cost):
        "Task12.ipynb" which uses 2015 data (thus GPS coordinates) to predict the three possible cost matrices and;
        "Task12-2020.ipynb" which uses 2020 data instead (thus zones, more generally) to do the same.
    "Task3": containing the three solving algorithms for task 3—the definition of algorithms and the usage of the cost matrices therein in order to choose a schedule that optimizes the delivery cost, for each stage of the shop demands inputs:
        put file 1 name and desc
        put file 2 name and desc
        put file 3 name and desc

The user can execute all of the cells sequentially in the order they're presented in in each file, starting with the first folder in order to generate the CSV files that contain the cost matrices to be used in the second folder (depending on the choice of using 2015 or 2020 data)..

The full list of required packages is available in requirements.txt. Run `pip install -r requirements.txt` or `conda install --file requirements.txt` to install them all at once.