# Assignment in DDMD class - NSCI0028/Term2/2022

## Collect and analyse existing materials data repositories and e-science platforms 
* website name: Aflow
* website URL: http://aflowlib.org/
* brief description: Automatic flow (Aflow) is a database developed and maintained by Duke University. It is built based on density functional theory (DFT) calculation with application programming interface (API) allowing user-defined material screening. The database contains over 726 million properties of 3.5 million different materials, including lattice structure, electronic, magnetic, mechanical and thermodynamic properties.
* Modelling Data 
  - [X] Density Functional Theory (DFT)/ Electronic Models
  - [ ] Molecular Dynamics/Atomistic Simulations
  - [ ] Coarse Grained Molecular Dynamics
  - [ ] Continumm 
  - [X] Other
        - if other specify: 
SYM (symmetry)
a robust model to identify symmetry properties for all entries, includes point-, factor-, space groups, site symmetries and Wyckoff positions. It determines a system-specific mapping tolerance that yields symmetry operations entirely commensurate with fundamental crystallographic principles[2].
CHULL
An autonomous thermodynamic stability analysis model has the function of identifying stable or coexist phases, equivalent structures, robust stability and decomposition reactions [3]. 
CCE (coordination corrected enthalpies) 
CCE is a method developed to solve the inaccurate formation enthalpies prediction made by the density functional theory [4].
POCC - Partial Occupation
AEL and AGL - Elastic Constants and Debye-Gruneisen model
XtalFinder - Identifying and classifying crystal prototypes
APL - Array Processing Language
QHA -Quasi-Harmonic Approximation

* Experimental Data: 
  * Describe the classes and types of materials covered. 
    *  Material of crystal structure.
* Access rights: 
  - [X] Free to all 
  - [ ] Commercial 
* Where is the data coming from:  
  - [ ] any one can upload data 
  - [X] provided by repository or platform owners
 
 
 ### Description:
Automatic flow (Aflow) is a DFT and API database managed by Duke University and is designed for material analysis. It contains 3.4 million types of materials’ information  regarding crystal energy bands, thermal and mechanical properties and so on. Two types of material structures are present in the database: experimental data from databases such as the Inorganic Crystal Structure Database (ICSD), the other are fictional structures, called structure prototypes. The properties of the structures are generated through quantum mechanics algorithms, the results are stored in the database for material choosing and training of machine learning models. Aflow offers the high-throughput calculation of alloys, intermetallics and inorganic compounds, as well as manipulation tools available for online operation[1].  User-defined material screening and automatic quantum mechanics calculations have made the database crucial in computational material discovery.


* References:

[1] D. Hicks et al., “AFLOW-SYM: platform for the complete, automatic and self-consistent symmetry analysis of crystals.,” Acta crystallographica. Section A, Foundations and advances, vol. 74, no. Pt 3, pp. 184–203, May 2018, doi: 10.1107/S2053273318003066.

[2] Cornell University [Internet]. [cited 2022 Jan 31]. Available from: https://arxiv.org/abs/1802.07977

[3] C. Oses et al., “AFLOW-CHULL: Cloud-Oriented Platform for Autonomous Phase Stability Analysis,” Journal of Chemical Information and Modeling, vol. 58, no. 12, pp. 2477–2490, Dec. 2018, doi: 10.1021/acs.jcim.8b00393.

[4] R. Friedrich et al., "Automated coordination corrected enthalpies with AFLOW-CCE," (in eng), 2021, doi: 10.1103/PhysRevMaterials.5.043803.




