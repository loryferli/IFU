# IFU
The full list of required packages is available in requirements.txt. Run `pip install -r requirements.txt` or `conda install --file requirements.txt` to install them all at once.

The code is divided into two main folders:

"Task12": containing two files both combining tasks 1 and 2 of the project---data cleaning, predictive model choice and construction of the three cost matrices (distance, time and financial cost):
- `Task12.ipynb` which uses 2015 data (thus GPS coordinates) to predict the three possible cost matrices and;
- `Task12-2020.ipynb` which uses 2020 data instead (thus zones, more generally) to do the same.

"Task3": containing the three solving algorithms for task 3---the definition of algorithms and the usage of the cost matrices therein in order to choose a schedule that optimizes the delivery cost, for each stage of the shop demands inputs:
- `routing_optimal.ipynb` contains the code for the optimal routing algorithm;
- `routing_closest_neighbor.ipynb` contains the code for the closest neighbor routing algorithm;
- `routing_savings.ipynb` contains the code for the savings routing algorithm.

The cells can be run sequentially in the order they're presented in each file, starting with generating the cost matrices CSV files in Task12.
