# alkane-STM-data

Jupyter notebooks for visualizing STM (Scanning Tunneling Microscopy) spectroscopy data published on Zenodo: https://doi.org/10.5281/zenodo.17469441

The analysis compares clean vs. alkane-contaminated graphite surfaces.

As opposed to the paper, some of the plots are prepared using Bokeh to allow easy zooming, panning, and exploring values on the plots.

Package versions used are explicitly printed in the notebooks for better reproducibility.

## Installation

Install required packages:

```bash
pip install -r requirements.txt
```

## Usage

The notebooks automatically download required data files from Zenodo if they're missing locally. Simply run:

```bash
jupyter notebook
```

Then open any of the plot notebooks (e.g., `plot_fig2a-d.ipynb`, `plot_fig3a.ipynb`, `plot_fig4.ipynb`).