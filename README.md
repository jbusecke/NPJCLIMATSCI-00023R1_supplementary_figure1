# npj Climate and Atmospheric Science - Reflections on the CLIVAR Early Career Scientists Symposium 2016 - Supplementary material for Figure 1


## Files provided
- `ECSS_Paper.ipynb` [jupyter notebook](https://github.com/jupyter) source used to create Figure 1 (see below).
Minor edits to the figure legend were done using [Adobe Illustrator](https://www.adobe.com/products/illustrator.html?sdid=KKQML&mv=search&s_kwcid=AL!3085!3!196928852571!e!!!!adobe%20illustrator&ef_id=WbfnlAAAAPgZDQuJ:20170915142601:s)
- `Country_loc.xlsx` Excel spreadsheet with circle locations for each country
- `ECSS_participants_anonymized.xlsx` Excel spreadsheet with participants
institution, the corresponding country and participants nationality.
- `ECSS_Paper_environment.yml` - environment file to create an anaconda python enviroment.

## Instructions

- Figure 1 was created in a [jupyter notebook](https://github.com/jupyter). Jupyter was obtained and executed from the [Anaconda Python Distribution](https://docs.anaconda.com/anaconda/). First, make sure you have Anaconda installed.

- Clone this repository, or download the files listed above.

- Setup the correct software packages within anaconda using the provided `ECSS_Paper_environment.yml` file ([more info](https://conda.io/docs/user-guide/tasks/manage-environments.html)).:

        conda env create -f ECSS_Paper_environment.yml

-Excecute the notebook with `source activate ECSS_Paper; jupyter-notebook ECSS_Paper.ipynb` and run all cells to reproduce the figure.
