# pyMOT
# Passive microrheology Analysis
This program analyzes the trajectories of a trapped particle inside an optical tweezer to obtain the rheological moduli G' and G'' of the surrounding medium. The calculation is done following the works of Tassieri et al. see the references below:
* Tassieri, M. Microrheology with Optical Tweezers: Principles and Applications.  (CRC Press, 2016).
* Preece, D. et al. Optical tweezers: wideband microrheology. Journal of optics 13, 044022 (2011).
* Tassieri, M., Evans, R., Warren, R. L., Bailey, N. J. & Cooper, J. M. Microrheology with optical tweezers: data analysis. New Journal of Physics 14, 115032 (2012).
* Tassieri, M. et al. Measuring storage and loss moduli using optical tweezers: Broadband microrheology. Physical Review E 81, 026308 (2010).

This program is published as a part of associated code for the manuscript "*Programmable Viscoelasticity in Protein-RNA Condensates with Disordered Sticker-Spacer Polypeptides*" by Alshareedah and coworkers.


Two Jupyter notebooks are included in this repository. One is for analyzing passive microrheology with optical tweezer data to extract the rheological moduli of the medium (pyPMOT). The second is to calculate the MSD from trajectory data obtained from trackmate for videoparticle tracking without optical tweezers to obtain the viscosity of the medium (pyVPT). These scripts are saved in the Code folder. 

The Data folder containts text files for the individual moduli of all the systems tested in the study. Each txt file has 7 columns (Frequency, G' from fitted autocorrelation, G'' from fitted autocorrelation, frequency, G' from raw autocorrelation, G'' from raw autocorrelation, viscosity from fitted autocorrelation). 
