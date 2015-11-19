# SpecDis
SpecDis is a handy tool to process the results of quantum-chemical ECD/UV, ORD, or VCD/IR calculations. It supports diverse software packages like ORCA, Gaussian03, Gaussian09, Turbomole (escf, ricc2),  NWChem, ADF, DALTON, or Grimme´s sTDA software (simplified TDDFT). 

SpecDis can visualize the computational results and has several possibilities to further process the spectra. Some of the features of SpecDis are:

    compare calculated ECD/UV, ORD, or VCD/IR spectra directly with experimental data (up to 5 curves)
    Gauss and Lorentz curve generation
    provide an enantiomeric ECD/VCD spectrum
    applying a "UV shift" or a scaling factor for VCD/IR
    arithmetic or Boltzmann weighted summation of spectra
    determining a similarity factor
    plot spectra with gnuplot in a "what you see is what you get" manner
    export spectral curves as *.xy files that can be processed with other software like Excel or Origin
    plot UV and CD traces of HPLC runs
    automatic extraction of heats of formation and spectral data from output files
    preliminary handling of ORD calculations with Gaussian03 and Gaussian09
    Boltzmann weighting of ORD values
    Similarity Factors for ECD/UV and VCD/IR spectra

Acknowledgments:

We are grateful to Dr. Pescitelli (University of Pisa; Italy) for helpfull discussions and beta testing of SpecDis.

System Requirements

SpecDis is tested under Windows 7 SP1 and Suse Linux Enterprise Server 11.3, Windows 8 has not been fully tested but the Win7 version  should work correctly. For Windows 7  (and 8) Specdis has to be installed on a partioned disk other than c:\, otherwise one might get administrator-right problems.Win XP and Vista are no longer supported!

The Interface to Gnuplot is tested up to version 5.0, png plotting will work with gnuplot 4.6 and higher only!

If you have any questions or suggestions feel free to send an email to torsten.bruhn@uni-wuerzburg.de 
