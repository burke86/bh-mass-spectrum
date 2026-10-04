# Black hole mass spectrum

Jupyter notebook and supporting catalogs for a histogram of detected black hole masses, covering GW progenitors and remnants, dynamical X-ray binaries, dwarf AGN, SDSS quasars, TDEs, and dynamical IMBHs.

The plot includes lower and upper mass gaps and annotations for selected sources. The existing figure is `bh_mass_det_spectrum.pdf`.

## Run

```sh
python -m pip install -r requirements.txt
jupyter lab fig.ipynb
```

Run the notebook from this repository directory. It reads the included text catalogs and LaTeX IMBH tables. It also requires the external SDSS catalog `dr16q_prop_May01_2024.fits`, currently referenced at `../stripe82_quasars/dr16q_prop_May01_2024.fits`. Place that file at the expected path or adjust the FITS path in the notebook. This 2.9 GB file is not included.

The notebook saves `bh_mass_det_spectrum.pdf` in the working directory. The notebook and catalogs are preserved as supplied; no scientific selections or calculations were changed.
