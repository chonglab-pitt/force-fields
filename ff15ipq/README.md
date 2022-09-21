### The Amber ff15ipq amino acid force field parameter files.

These files for the Amber ff15ipq force field are distributed with releases of Amber and Ambertools.
There are two sets of files corresponding to amino acids in SPC/Eb water solvent and in vacuum. 

To manually replace the solvated version of the files in Amber (v16+), please do the following:

1) Copy leaprc.protein.ff15ipq to your $AMBERHOME/dat/leap/cmd folder
2) Copy parm15ipq_10.3.dat to your $AMBERHOME/dat/leap/parm folder
3) Copy amino15ipq_10.0.lib, aminoct15ipq_10.0.lib, aminont15qip_10.0.lib to your $AMBERHOME/dat/leap/lib folder


Then within tleap, run the following commands:

  source leaprc.protein.ff15ipq

For the force field in vacuum, go through same steps with the 15ipq-vac versions of each file instead.

For more information, feel free to consult the paper (https://doi.org/10.1021/acs.jctc.6b00567). 
