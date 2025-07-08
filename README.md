# SolarFlareFluxPredictorGUI
GUI for flux magnitude forecasting models trained using SolarFlareFluxPredictor, found at https://github.com/MChoquette01/SolarFlareFluxPredictor

--- 
## To Set-up
---
### 1. Download the Repository

* Navigate to the location you would like to access `SolarFlareFluxPredictorGUI` on your local machine.
* In the command line use `git clone https://github.com/MChoquette01/SolarFlareFluxPredictorGUI.git`. 
 
You now have the `SolarFlareFluxPredictorGUI` package.

### 2. Python Virtual Environment

To avoid polluting your base python environment let's create a virtual Python environment to work in.

**Conda** <sub><sup>[recommended]</sup></sub>

	We can create the environment with [Conda/Miniconda](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) where we can just type `conda create -n solarflarefluxpred-env python==3.11 pip` in the command line.

	* Now we can activate the environment with `conda activate solarflarefluxpred-env`; and
	* deactivate with `conda deactivate`.
	* *Note: we need to have python 3.11, because a scikit-learn module does not work with newer python versions*

	(See [here](https://docs.conda.io/en/latest/miniconda.html) for information on installing miniconda.)
	
### 3. Installing `SolarFlareFluxPredictorGUI` requirements

Make sure you are in the `SolarFlareFluxPredictorGUI` directory and have the activated the virtual environment, type `pip install -r requirements.txt`. This install all the required packages used in `SolarFlareFluxPredictorGUI`.

Now, as long as you are in your virtual environment, you can use the methods in `SolarFlareFluxPredictorGUI` without issue while in any directory.

---
## To Run
---
To run the GUI, simply enter `python GUI.py` into your terminal, in the `SolarFlareFluxPredictorGUI` folder.

A detailed explanation of the GUI is TBD.

When finished running, summary data will be located in the `Artifacts` folder, with the name of the folder being the start date/time that the GUI was opened.