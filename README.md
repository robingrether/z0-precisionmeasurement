# z0-precisionmeasurement
Precision measurements and tests of the Standard Model using OPAL data at LEP

## All analysis code is in the jupyter notebook `z0-experiment_MyWork.ipynb`

1. Install [anaconda](https://docs.anaconda.com/anaconda/install/) (miniconda probably works too?).
2. `conda env create` reads the `environment.yml` file in this
   repository, creates a new env and installs all necessary packages
   into it.
3. Activate the new env: `conda activate z0-env`
4. Start `jupyter-notebook` (or `jupyter-lab` if you prefer) in the
   environment. This will usually open your browesr automatically. If
   not the link is printed to the console too.
5. Open `z0-experiment_MyWork.ipynb`. You can now run the code top to bottom.
	Some cells with a lot of plotting are "dectivated" to avoid cluttering the notebook. 
	Set `if False` to `if True` there to show some non-necessary visualizations.

6. Open `grope-stuff/grope-analysis.ipynb` to check out our analysis of the Grope example events.
	It's not necessary for the rest of the code, since we defined our cuts using the MC dataset.

## Attention:

Calculated values may vary between different executions because of the used Gaussian sampling for error propagation.