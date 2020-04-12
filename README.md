# PS1zxcorr

This code was created by Alessandro Marins (University of Sao Paulo) and is owned by BINGO Telescope.
Its use is to extract optical data from Pan-STARRS1 telescope.
Any question about your operation, please, contact me in alessandro.marins@usp.br

To use it, run run_PS1Code.py.

The variables and conditions are in parameters.ini.
Any variable can be altered in terminal with "--" and the same name of the variable in parameter.ini plus underline and the name of class, except the General class, in this use it only variable name.
All the letters in minuscule.

For example:
python run_PS1Code.py --nside 1024 --use_constraint False --band_flags i --use_declination_strips False

You need to check if there are the Python libraries: numpy, healpy, sys, os, ConfigParser(python2) or configparser(python3), astropy, mastcasjobs*, requests, re, json and argparse.

Ps.: This code is currently only available for python2. Your adaptation to python3 is being performed. Because the version of mastcasjobs used is 0.0.1 and not the last, 0.0.2.

*https://github.com/rlwastro/mastcasjobs
