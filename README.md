# TARDIS Summer School 2025
## Hosted at Michigan State University
### July 28th - Aug 1st

This repository contains student and instructor versions of each notebook exercise used in the 2025 TARDIS Summer School. The summer school exercise notebooks are in day directories. 

Day 0 - To be completed before the summer school. The exercise inside this directory was mainly to introduce participants to astropy units, pandas dataframes, and more generally jupyter notebooks and python for those unfamiliar. 

Day 1 - A short monte carlo radiative transfer introduction wherein participants build their own monte carlo radiative transfer simulation using energy packets that describe the flow of energy through material. 

Day 2 - An introduction to computational plasma modeling, where students begin by solving for the ionization and excitation states of atoms in a plasma assuming full Local Thermodynamic Equilibrium (LTE) conditions. In the second exercise students explore the implications of their plasma solver, as pertains to supernova ejecta, and think about calculating optical depths based on their plasma conditions.

Day 3 - An introduction to TARDIS, that begins with inputs to TARDIS and how a user can make sure they are running TARDIS with sensible conditions. The exercises in this day also connect internals of TARDIS to the concepts pieces of code they have built on days 1 and 2. 

Day 4 - A deeper exploration of TARDIS, where participants connect different configurations of TARDIS to the physical principles they have learned throughout the summer school. Participants also learn to use TARDIS visualization and analysis tools to make insights about what happens in the simulation and how you can learn about transient ejecta with TARDIS. 


## An Important Note

The notebooks in repository were built to use TARDIS as it existed at the time of the summer school and (are likely to be but) are not guaranteed to work in future versions. You can find a version of TARDIS that works with these notebooks here  https://github.com/tardis-sn/tardis/releases/tag/release-2025.08.03

The notebooks are specifically not likely to reflect the optimal way to run or access the internals of TARDIS in the future. At the time of the summer school, TARDIS was undergoing relatively large restructures that move around some of the pieces that were looked at in these notebooks. We do not guarantee that you will be able to access TARDIS in the same way for future versions.

Also note that there are known mistakes in some of these notebooks. Once again, this repository contains the notebooks as they were given at the time of the summer school. The instructor versions contain either working code or some explanation towards questions that were asked in the notebooks. The explanations are not particularly complete or completely correct and were included mainly to give instructors direction to help answer student questions. If you decide to work through these notebooks on your own, don't take the instructor solutions as perfect answers to questions asked. 