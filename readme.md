A 30-year reconstruction of the Atlantic meridional overturning circulation shows no decline.
============

Authors
--------
[Emma L. Worthington](https://emmaworthington.com)<sup>1</sup>, [Ben I. Moat](https://www.researchgate.net/profile/Ben_Moat)<sup>2</sup>
, [David A. Smeed](https://www.researchgate.net/profile/David_Smeed)<sup>2</sup>,
Jennifer V. Mecking<sup>2</sup>, Robert Marsh<sup>1</sup>, and [Gerard D. McCarthy](https://www.researchgate.net/profile/G_Mccarthy3)<sup>3</sup>.

1: [University of Southampton](https://www.soton.ac.uk), European Way, Southampton, SO14 3ZH, UK.

2: [National Oceanography Centre](https://www.noc.ac.uk), European Way, Southampton, SO14 3ZH, UK.

3: [ICARUS](https://www.researchgate.net/lab/ICARUS-Maynooth-University-Peter-W-Thorne), Department of Geography, Maynooth University, Maynooth, Co. Kildare, Ireland.

Key Points
----------

  - A reconstruction of the AMOC using an empirical regression model shows no decline between 1981 and 2015.
  - The resolution of the reconstruction is improved enough to show decadal and pentadal variability
  - The dynamics of the AMOC at 26°N mean that single-layer models are insufficient to reconstruct low frequency changes associated with deep water masses.

Abstract
--------
A decline in Atlantic meridional overturning circulation (AMOC) strength has been observed between 2004 and 2012 by the RAPID array with this weakened state of the AMOC persisting until 2017. Climate model and paleo-oceanographic research suggests that the AMOC may have been declining for decades or even centuries before this, however direct observations are sparse prior to 2004, giving only ‘snapshots’ of the overturning circulation. Previous studies have used linear models based on upper layer temperature anomalies to extend AMOC estimates back in time, however these ignore changes in the deep circulation that are beginning to emerge in the observations of AMOC decline. Here we develop a higher fidelity empirical model of AMOC variability based on RAPID data, and associated physically with changes in thickness of the persistent upper, intermediate and deep water masses at 26° N and associated transports. We applied historical hydrographic data to the empirical model to create an AMOC time series extending from 1981 to 2016. Increasing the resolution of the observed AMOC to approximately annual shows multi-annual variability in agreement with RAPID observations, and that the downturn between 2008 and 2012 was the weakest AMOC since the mid-1980s. However, the time series shows no overall AMOC decline as indicated by other proxies and high resolution climate models. Our results reinforce that adequately capturing changes to the deep circulation is key to detecting any anthropogenic climate change-related AMOC decline.

Status
----------
  The [paper](https://emmaworthington.github.io//) was published in
  in [Ocean Science](http://agupubs.onlinelibrary.wiley.com/agu/journal/10.1002/(ISSN)1944-8007/),
  [doi: 10.1002/2016GL071349](http://onlinelibrary.wiley.com/doi/10.1002/2016GL071349/full).
  [Supporting information](https://github.com/crocha700/UpperOceanSeasonality/blob/master/writeup/rocha_etal_supporting-info.pdf) and [figures](https://github.com/crocha700/UpperOceanSeasonality/blob/master/writeup/figs/) are also available. Comments, questions, and suggestions are extremely welcome
  and warmly appreciated. Feedback can be submitted through github [issues](https://github.com/crocha700/UpperOceanSeasonality/issues) or via e-mail to
  Emma Worthington (emma.worthington@soton.ac.uk).

Code
----
The majority of analysis was done using code written by the first author in Python. This code uses the [Scientific
Python stack](https://www.scipy.org/install.html) and the excellent [xarray](http://xarray.pydata.org/en/stable/) package. A subset of that code is made available here, sufficient to reproduce the results.

The project also adapted code developed by the [RAPID project team](https://www.rapid.ac.uk) for processing mooring data, this code is not shared here. The project also uses a small piece of Matlab code developed by [Eleanor Frajka-Williams](https://www.researchgate.net/profile/Eleanor-Frajka-Williams) which uses the [jlilly Matlab package](http://jmlilly.net/software.html).


Data
------
Data from the RAPID AMOC monitoring
project are funded by the Natural Environment Research Council and are freely available from http://rapid.ac.uk/rapidmoc/rapid_data/datadl.php. (https://doi.org/10.5285/8cd7e7bb-9a20-05d8-e053-6c86abc012c2). The Florida Current cable and section data are made freely available on the Atlantic Oceanographic and Meteorological Laboratory web page (https://www.aoml.noaa.gov/phod/floridacurrent/) and are funded by the DOC-NOAA Climate Program Office – Ocean Observing and Monitoring Division. The World Ocean Database (WOD) is an NCEI product and an IODE (International Oceanographic Data and Information Exchange) project. The work is funded in partnership with the NOAA OAR Ocean Observing 25 and Monitoring Division. WOD2018 data are freely available at https://www.nodc.noaa.gov/OC5/WOD/pr_wod.html. The ECMWF ERA-Interim reanalysis data are freely available at
https://apps.ecmwf.int/datasets/.

Support
-------
This research has been supported by the Natural Environment Research Council (grant nos. NE/L002531/1 and NE/N018044/1), Horizon 2020 (grant no. 727852), the National 55 Science Foundation (grant no. 1332978), the National Oceanic and Atmospheric Administration (grant no. 100007298), the European Regional Development Fund (grant no. PBA/CC/18/01), and the Climate Program Office (grant no. 100007298).

Acknowledgments
----------------
[Penny Holliday](https://www.researchgate.net/profile/Naomi_Holliday) provided helpful feedback and advice.