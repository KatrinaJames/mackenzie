# Global Dividend Equity Analysis

The repo contains the analysis and app comparing the following funds:
- Fidelity Global Dividend Fund
- CI Global Dividend
- Dynamic Global Dividend

The analysis is limited to F-class versions of these fund for an apples-to apples comparison.

## How to run locally
- Build the conda environment with `conda env create --file environment.yaml`
- Activate the environment with `conda activate mackenzie`
- Launch either `jupyter lab` or `jupyter notebook`

## Deployed web app
- View on mybinder [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/KatrinaJames/mackenzie/HEAD?urlpath=%2Fdoc%2Ftree%2Fapp%2Fapp.ipynb?theme=dark)
- Or run locally using `python -m voila app.ipynb --theme=dark` from the `app` directory

## Conventions and layout
- Front-end of the app is located in the `app` directory
- Artifacts used for analysis are located in the `data` directory