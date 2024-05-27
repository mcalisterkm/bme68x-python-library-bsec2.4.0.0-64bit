# bme68x-python-library-bsec2.4.0.0-64bit
Alpha version of the bme68x python wrapper for BSEC 2.4 with the 64bit BSEC library

As this includes the PI/Arm 64 bit BSEC library, there is no need to copy the BSEC software.

How to install the extension with BSEC

- clone this repo to a desired location on you hard drive
- open a new terminal window inside the bme68x-python-library-main folder 
```
  sudo python3 setup.py install

  or to install under venv use
  path/to/venv/bin/python3 setup.py install
```
Note: The BSEC 2.4 file structure is included in this repo but there are no BSEC binaries other than the PI 64 bit library posted on the BoschSensortec community forum. 
