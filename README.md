# WP6-host-guest-binding
This folder contains initial conditions generated with molecular docking with two scoring functions and all charge sets employed in our extensive end-point free energy calculations on the carboxylated-pillar[6]arene host-guest systems. The full text of the WP6 end-point series can be accesssed at
1. The standard end-point procedure https://chemrxiv.org/engage/chemrxiv/article-details/62bc8a7a91954980dcd92eeb 
(published version https://link.springer.com/article/10.1007/s10822-022-00475-0)
2. Trained end-point scheme and dielectric constant https://chemrxiv.org/engage/chemrxiv/article-details/62c10e5852acb774027c6129
3. TBA later

For the chemical structures presented in paper 1, there is a typo: G3 has a -NH3+ group rather than -NMe3+, but the docking structures and parameter files uploaded here (the current repository) are correct. 

The AM1-BCC charge scheme performs AM1 optimization and then computes charges by combining AM1 Mulliken charges and BCC corrections. 

The two RESP charge sets are obtained with similar numerical procedures, including B3LYP/6-31G* optimization and then ESP scanning at some ab initio levels to generate the reference data. The difference lies in the level for the ESP scan. RESP-1 follows the traditional HF/6-31G* regime, while the RESP-2 scheme follows a more modern level of B3LYP/def2-TZVPP plus the IEFPCM solvation. The reason for choosing these two levels for ESP scanning is the notable difference between the ESP data at the two levels. More detailed analyses of molecular ESP are provided in the first paper of this WP6 end-point series.  

The free energy estimates obtained with all parameter combinations and end-point calculation procedures are included in the supporting information of each paper and thus are not included here. 

The initial bound configurations obtained from molecular docking with Autodock Vina are also provided here. Two scoring functions including Autodock4 and Vina are employed. Structural analyses presented in the first paper suggest significant differences between the docked structures produced by the two scoring functions. 

