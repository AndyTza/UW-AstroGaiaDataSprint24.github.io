---
title: Gaia DR3 Data Resources
---

If you're unsure on what you want to work on, we have a running list of ideas ([here](https://docs.google.com/document/d/1ibuPqcOPDiiuD12GXNWYgUpU53UAR1QQWI-UN5kzotY/edit?usp=sharing)). Additionally, you might find the introduction slides useful ([here](https://docs.google.com/presentation/d/1Njbu2Nk1q7dunjGVb2qnmydA5MqXergVMHjwqCO-sQk/edit?usp=sharing)). 

Below we have compiled a list of **many** data resources and ways to access the Gaia data and the myriad of its auxiliary science data products. 


# Gaia Data Products
Here is a list of Gaia data related data products you might find interesting:
- [Gaia Data Data Release 3 Gaia DR3 content](https://www.cosmos.esa.int/web/gaia/dr3)
- [Gaia Photometric Science Alerts](http://gsaweb.ast.cam.ac.uk/alerts/home)
- [Gaia X - Photometric Alerts](http://gsaweb.ast.cam.ac.uk/alerts/gaiax/)
- [All Gaia Related Products - Vizier](https://vizier.cds.unistra.fr/viz-bin/VizieR-2)
- [Gaia Focused Product Release](https://www.cosmos.esa.int/web/gaia/focused-product-release)
- [StarHorse DR2](https://vizier.cds.unistra.fr/viz-bin/VizieR?-source=I/349)
- [Bailer-Jones+, 2021](https://vizier.cds.unistra.fr/viz-bin/VizieR?-source=I/352)
- [GaiaXP The Gaia BP/RP spectra package](https://gaia-dpci.github.io/GaiaXPy-website/)

## Related Data Products

Here is a list of auxiliary datasets from various surveys and telescopes you can possibly use:

- [Lightkurve](https://docs.lightkurve.org/) - A friendly Python package for making discoveries with Kepler & TESS.
- [MAST](https://archive.stsci.edu/) - Barbara A. Mikulski Archive for Space Telescopes (MAST) is an astronomical data archive focused on the optical, ultraviolet, and near-infrared.
- [Hubble Legacy Archive](https://hla.stsci.edu/) - The Hubble Legacy Archive (HLA) is designed to optimize science from the Hubble Space Telescope by providing online, enhanced Hubble products and advanced browsing capabilities.
- [NASA/IPAC Extragalactic Database](https://ned.ipac.caltech.edu/)
- [Transient Naming Server](https://www.wis-tns.org/) - Classifications of transient phenomena in the universe. 
- [All-Sky Automated Survey for Supernovae (ASAS-SN) projet](https://www.astronomy.ohio-state.edu/asassn/) - All-sky optical time-domain survey.
- [NASA/IPAC Infared Science Archive](https://irsa.ipac.caltech.edu/frontpage/) - Includes optical and infrared observational data.
- [eROSITA-DE Data Release 1](https://erosita.mpe.mpg.de/dr1/index.html) - DR1 consists of 20626.5 square degrees, which have a variety of effective exposure values, ranging from ∼100 seconds in the Ecliptic equator to more than 10,000 seconds close to the Ecliptic pole in the 0.6—2.3 keV energy band.
- [Cogsworth](https://cogsworth.readthedocs.io/en/latest/) - A Python package for performing self-consistent population synthesis and galactic dynamics simulations.



# Data Access
If you have never used or queried Gaia data, you should look at this list. Below we organized a list of several ways on how users can access the Gaia data-related products to start their projects. The organizing members will also be around if you have any specific questions about how to access data. 

## Local Tools 
We will be hosting a [HiPSCated](https://ui.adsabs.harvard.edu/abs/2023AAS...24110506W/abstract) version of Gaia DR3 here. If you are keen to use this version, participants are encouraged to use the latest tool developed by the LINCC Frameworks [Large Survey Database (LSDB)](https://github.com/astronomy-commons/lsdb).

- Data is stored [here](https://epyc.astro.washington.edu/~lincc-frameworks/hipscat_surveys/gaia_dr3/).
- [Sample tutorial](https://lsdb.readthedocs.io/en/latest/notebooks/ztf_bts-ngc.html)
- [For users with access to epyc, you can also see this tutorial](https://github.com/dirac-institute/ZTF_FG_BoyajianSearch/blob/main/analysis/notebooks/tda-uw-demo/hrdiagram-timeseries-ztf-gaia.ipynb)


##  Online Tools

- [ESA Gaia Arhive](https://gea.esac.esa.int/archive/) - Features include: Basic query, ADQL query, and Single Object Search

- [VizieR Notebook Generator Example](https://cdsarc.cds.unistra.fr/vizier/notebook.gml?source=I/355)

- [Astropy Gaia TAP+](https://astroquery.readthedocs.io/en/latest/gaia/gaia.html)

- [TOPCAT](https://www.star.bris.ac.uk/~mbt/topcat/) - TOPCAT is an interactive tool designed to view and edit tabular data, including Gaia products. It supports various data formats, offers advanced visualization and analysis features, and operates as a standalone application.

- [Data Carpentry Tutorial working with Gaia](https://datacarpentry.org/astronomy-python/)

- [NOIRLab JupyterHub](https://datalab.noirlab.edu)
  - :warning: All participants must register [here](https://datalab.noirlab.edu/account/register.html)
  - All available Gaia products hosted by NOIRLab [here](https://datalab.noirlab.edu/gaia.php).
  - Jupyter notebook science example demos [here](https://datalab.noirlab.edu/docs/manual/UsingAstroDataLab/ScienceExamples/index.html)
  - Getting started with NOIRLab Jupyter notebooks [here](https://datalab.noirlab.edu/docs/manual/UsingAstroDataLab/JupyterNotebooks/JupyterNotebooks.html#sec-jupyternotebooks)

- [GaiaAlertPy](https://gaiaalertspy-docs.readthedocs.io/en/latest/)
  - Please note, Andy Tzanidakis might be hacking on this data product during the workhop! If it sounds interesting, we welcome collaborators.

- [Tap VizieR](https://tapvizier.u-strasbg.fr/adql/?gaia)


