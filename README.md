# Alchemical free energy calculations with BioSimSpace

### Aimed at: 
Anyone interested in learning how to use BioSimSpace to setup, run, and analyse alchemical free energy simulations. 


### Requirements: 
- Basic python knowldege
- Basic understanding of molecular simulations
- Some background knowledge in statistical mechanics is helpful but not essential

### Abstract: 
Alchemical free energy calculations can be used to efficiently compute binding free energies between a ligand and a protein or hydration free energies of a small molecule. In the last few years, the use of such methods has gained momentum not only within academia but also within the pharmaceutical industry. In order to run alchemical free energy simulations, a series of molecular dynamics simulations need to be carried out. The first part of this workshop will look at setting up and running binding free energy calculations with BioSimSpace, whereas the second part will introduce best practices for their analysis. As part of the analysis, we will cover thermodynamic integration, MBAR, as well as how to choose good simulation overlap using metrics from an overlap matrices.

### Training Material

The workshop consists of a series of Jupyter notebooks. These are available on the
<a href="https://notebook.biosimspace.org" target="_blank">workshop jupyter server</a>
and can be downloaded from the <a href="https://github.com/ccpbiosim/biosimspace_workshop" target="_blank">GitHub repository</a>.

Once you have started the server, navigate to the `free_energy_workshop` directory and you will find the
notebooks there. These training materials will teach you more about how to use BioSimSpace for alchemical free energy calculations.

### Part 1: Alchemical free energy setup
This part will look at how to setup an alchemical free energy simulation with BioSimSpace using the notebook 

[01\_Setup.ipynb](01_Setup/Exercise_01.ipynb)

### Part 2: Alchemical free energy simulation analysis
The second part focuses on how to analyse the alchemical free energy simulations, as well as some tips on best practices. This is done in two notebooks:

[02\_Analysis\_ethane\_methanol.ipynb](02\_Analysis\_ethane\_methanol/Exercise_02.ipynb)   
[03\_Analysis\_Lysozyme .ipynb](03_Analysis_Lysozyme/Exercise_03.ipynb)

### Contact:

Antonia Mey [@ppxasjsm](github.com/ppxasjsm)   
Lester Hedges [@lohedges](github.com/lohedges)   
Please raise issues on github with bugs or comments. 


### Licence:
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" title='This work is licensed under a Creative Commons Attribution 4.0 International License.' align="left"/></a>