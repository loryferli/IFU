# IFU
The code is divided into two different files: "Task12.ipynb" and the "Task3" folder, containing the three solving algorithms for task 3.

The first, as the name entails, includes our work for tasks 1 and 2. Namely our data cleaning, predictive model choice and fitting and finally the construction of the three cost matrices (distance, duration and financial cost).

The routing files include our work for task 3. Namely the definition of algorithms and the usage of the cost matrices therein in order to choose a schedule that optimizes the delivery cost, for each stage of the shop demands inputs.

The user can execute all of the cells sequentially in the order they're presented in in each file, starting with the first. Regarding the second file, running the cells will require the three csv files given in the .zip file this README file is contained in (or running the respective cells in the first file). These CSVs are the resulting cost matrices of the first file.

The full list of required packages is available in requirements.txt. Run `pip install -r requirements.txt` or `conda install --file requirements.txt` to install them all at once.
