# ClaraVista's solution for the 2022 Hackathon IIEP-UNESCO

This repository contains the code submitted by the ClaraVista team for the 2022 edition of the IIEP-UNESCO Hackathon.
The challenge we tried to solved is the challenge number 2, described [here](https://box.iiep.unesco.org/s/YxZiiATTsAsbyMK/download/Hacking%20EDplanning_Challenge%202%20brief.pdf).

More documentation can be found in the following links:
- complete challenge documentation: https://box.iiep.unesco.org/s/YxZiiATTsAsbyMK/download/Hacking%20EDplanning_Challenge%202%20brief.pdf
- Github's deposit of the challenge: https://github.com/iiepdev/HackingEDPlanningV2-Challenge2

## Using this deposit

This deposit should be self-sufficient and contain all the necessary documentation for you to understand what we did during this challenge. It is composed by the following files:
- [user documentation](#user_guide.pdf): the user documentation describing the process we followed. It describe amongst others the process you can follow to generate the necessary data for the computations. All the data used for this challenge are open-source and available freely on the internet. This user guide also describe the manipulation you can perform with [QGIS](https://www.qgis.org/fr/site/) in order to compute the temporal animation.
- [computation notebook](#computations.ipynb): the python implementation of the computations. Once you have generated the necessary data (you can also choose to use the provided one if you simply want to fiddle with the code), head to this notebook to perform the computation and see the visualizations.
- [qgis template project](#temporal_visualization.qgz): a template QGIS project where some of the manipulations required for the temporal animation. If you load this project into your system's QGIS installation, you should only have to replace the data source and obtain our temporal animation. All of this is described in the [user guide](#user_guide.pdf). If this fails, the [user guide](#user_guide.pdf) also describes the steps necessary to reconstruct this animation from scratch.
