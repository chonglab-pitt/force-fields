To use the new ff15ipq-m force field in Amber (v16+) please do the following:

1) Copy leaprc.mimetic.ff15ipq to your $AMBERHOME/dat/leap/cmd folder
2) Copy ff15ipq-m.lib to your $AMBERHOME/dat/leap/lib folder
3) Copy frcmod.ff15ipq-m to your $AMBERHOME/dat/leap/parm folder


Then within tleap, run the following commands:

source leaprc.mimetic.ff15ipq


For more information, feel free to consult the ff15ipq-m tutorial (https://ambermd.org/tutorials/advanced/tutorial36/index.php) or the paper (https://aip-scitation-org.pitt.idm.oclc.org/doi/10.1063/5.0019054). 