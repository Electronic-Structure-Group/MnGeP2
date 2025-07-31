# MnGeP2
Data files related to MnGeP2 paper Ilteris Turan et al.
# The data files directly related to each figure are in the folder Data Files, seperated into Main Paper and Supplemetal Material.

# In Main Paper:
1) Fig.1 is a .vesta file for the crystal structure which can be opened with the VESTA software available at  https://jp-minerals.org/vesta/en/download.html
2) Fig.2 (a) and (b) contain the QSGW^BSE band structure files in the format of bnds.ext used in the Questaal suite which are described at https://www.questaal.org/docs/input/data_format/
To make the plots in the paper these data files are processed using the plbnds code available at 
https://www.questaal.org/docs/misc/plbnds/
3) Fig.3 is a .agr generated using xmgrace
https://plasma-gate.weizmann.ac.il/Grace/
They can also be used with https://sourceforge.net/projects/qtgrace/
It contains the data sets for each xy curve internally.
4) The data for Fig.4(a) are provided in the same band structure file format as in Fig.2 and for Fig.4(b) each valence and conduction band in meV are provided in an Microsoft Excell sheet.
5) Data for Fig.5 are in .agr format as in Fig.3.
6) The data for Fig.6 are in Excell spreadsheet format.
7) The heatmap data (chipm_rsa.h5) in Fig.7 are in .h5 HDF5 format
The simple xy line is in ascii data file for the spin wave energy. It lists the q-point coordinates followed by the SW energies in meV 
8) Fig.9 data are Questaal .bnds files, same as in Fig.2 and Fig.4(a) above.
--------
The Exchange Interaction Tables folder contains the output files (llmgf11-x0inv) including Heisenberg exchange interaction data for each magnetic site (i,j) combination, as well as the Mean Field and Tyablikov (RPA) estimates of the critical temperature obtained for pure crystal (Table II), effects of carrier doping (Table III), MnGe_antisite (Table IV). 

# In Supplemental Material:
1) Fig.1 contain ferromagnatic (a)GGA,(b)GGA+U,(c)G0W0,(d)QSGW^RPA,(e)QSGW^BSE band structure files in bnds.ext format used in Questaal suite.
2) Fig.2 is the same as Fig.1 for the antiferromagnetic ordering. 
3) Fig.3 contain band structure files in bnds.ext format within the (a)GGA+U, (b)G0W0, and (c) QSGW_RPA levels, for the SGNP path where the major altermagnetic spin splittings occur.
4) Fig.4 contain the band structure file for the QSGW_RPA level including the spin-orbit coupling. Here, the antiferromagnetic ordering is noncollinear. 
The file is in the bnds.ext format, where, for each q_point, the first set lists all of the bands and the second set lists the weights of the bands' majority spin character ranging from 0 to 1. The majority and minority spin characters must add up to 1.   
--------
The Exchange Interaction Tables folder contains the llmgf11-x0inv output files (same as in the Main Paper folder), for the GGA and QSGW_RPA approximations.

--------
The Meta Files folder contains Questaal source files with settings for how the data were generated for each system
ctrl, site, syml (for MΓXPNΓS and SGNP paths), and basp files are available for Questaal users. 
