Acknowledgement:

These data are being made available to the public as a service to the astronomical community.
If you use RoboPol data in your research, we request that you cite the related publication
(https://arxiv.org/abs/2012.00008), allowing us to keep track of the impact of our work,
and that you include the following acknowledgement:
'This research has made use of data from the RoboPol programme, a collaboration between Caltech,
the University of Crete, IA-FORTH, IUCAA, the MPIfR, and the Nicolaus Copernicus University, which was
conducted at Skinakas Observatory in Crete, Greece.'

Abstract:

We present uniformly reprocessed and re-calibrated data from the RoboPol programme of optopolarimetric
monitoring of active galactic nuclei (AGN), covering observations between 2013, when the instrument was
commissioned, and 2017. In total, the dataset includes 5068 observations of 222 AGN with Dec > -25 deg.
Average quantities summarising optopolarimetric behaviour  (average degree of polarization, polarization
variability index and preferred polarization angle) are also provided for each source we have observed
and for the time interval we have followed it. 

Data contents:

This dataset contains two tables denoted A1 and A2 in the related publication.

1) sample.tab (A1) provides information on the observing sample and average polarization parameters of sample sources.
This table contains the following columns:
#  1: J2000 name.
#  2: Alternative source identifier.
#  3: Right ascension [h:m:s]
      according to NASA/IPAC Extragalactic Database.
#  4: Declination [d:m:s]
      according to NASA/IPAC Extragalactic Database.
#  5: Redshift
      in some cases the value of redshift is followed by a note that can be:
       (*) - non spectroscopic redshift;
       (l) - lower limit on redshift;
       (m) - multiple values are present in literature.
#  6: Redshift reference
      in astrophysics data system https://ui.adsabs.harvard.edu/ bibliographic format.
#  7: Sample identifier:
       (1) gamma-ray-loud sub-sample from the 'June survey' sample;
       (2) gamma-ray-quiet sub-sample from the 'June survey' sample;
       (3) gamma-loud sub-sample from the monitoring sample;
       (4) gamma-ray-quiet sub-sample from the monitoring sample;
       (5) additional sample of 68 hand-picked sources of high interest;
       (6) ISP/HSP blazar sample.
#  8: Aperture [arcsec]
      either numeric value in the case of fixed aperture or 'v' symbol meaning variable aperture
#  9: Number of measurements.
# 10: Number of seasons.
# 11: Median time sampling interval [d].
# 12: Mean intrinsic polarisation fraction [%].
# 13: Intrinsic modulation index of the polarization fraction.
# 14: Variability index of the EVPA.
# 15: Preferred EVPA orientation of less variable sources [deg].

2) monitoring_data.tab (A2) provides information on the observing sample and average polarization parameters of sample sources.
This table contains the following columns:
# 1:  J2000 name
# 2:  Julian date
# 3:  Relative Stokes parameter Q/I before the instumental polarization correction
# 4:  Uncertainty of the relative Stokes parameter Q/I before the instumental polarization correction
# 5:  Relative Stokes parameter U/I before the instumental polarization correction
# 6:  Uncertainty of the relative Stokes parameter U/I before the instumental polarization correction
# 7:  Relative Stokes parameter Q/I after the instumental polarization correction
# 8:  Uncertainty of the relative Stokes parameter Q/I after the instumental polarization correction
# 9:  Relative Stokes parameter U/I after the instumental polarization correction
# 10: Uncertainty of the relative Stokes parameter U/I after the instumental polarization correction
# 11: Fractional polarization [%]
# 12: Uncertainty of fractional polarization [%]
# 13: The electric vector position angle [deg]
# 14: Uncertainty of the electric vector position angle [deg]
