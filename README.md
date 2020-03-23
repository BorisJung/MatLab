# Collection of MatLab scripts

## List of scripts

- 01 - Low Jitter Hard Limiter Design Tool 
- 02 - Image Source Model Binaural Room Impulse Response Script

### 01 - Low Jitter Hard Limiter Design Tool

This tool was developed while designing the hard limiter input stage for the phase noise measurement system during the work on my Bachelor's Thesis.

It makes use of the design guide for low jitter hard limiters by Oliver M. Collins published in the following IEEE paper:

[The Design of Low Jitter Hard Limiters](https://ieeexplore.ieee.org/document/494304)

The script is meant to be used by executing ***jitter_calc.m*** in MatLab. It starts with a user input window, where the given design parameters from the collins paper are entered. The script then calculates gain distribution, time constants, resulting jitter and some other parameters.

### 02 - Image Source Model Binaural Room Impulse Response Script

This script was developed as part of a portfolio exam during my master's studies at TU Berlin. It needs the [Auditory Modeling Toolbox](http://amtoolbox.sourceforge.net/), the [Large Time-Frequency Analysis Toolbox](https://ltfat.github.io/) as well as the [SOFA MatLab API](https://www.sofaconventions.org/mediawiki/index.php/SOFA_(Spatially_Oriented_Format_for_Acoustics)) included in the corresponding subfolder.

Once all set up, it calculates the binaural room impulse response of a rectangular room with parameters given by input variables. See pictures subfolder or ***_project_paper.pdf*** for an overview of the functionality.








