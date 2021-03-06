## DEMReg
Calculate the Differential Emission Measure (DEM) from solar data using regularized inversion in SSWIDL.

Note that this repo contains 3 versions of the DEMReg code:

* Original sswidl version from [Hannah & Kontar (2012)](https://doi.org/10.1051/0004-6361/201117576) which takes a single set of data (pixels, lines etc) for any instrument (just need to supply temperature response) in [idl_org/](https://github.com/ianan/demreg/tree/master/idl_org)
* Update of sswidl mapping version from [Hannah & Kontar (2013)](https://doi.org/10.1051/0004-6361/201219727) which can do any form of data (maps, single pixels) and for any instrument (just need to supply temperature response), in [idl/](https://github.com/ianan/demreg/tree/master/idl)
* Python version based off of [idl/](https://github.com/ianan/demreg/tree/master/idl) which again can take any data format and any instrument, in [python/](https://github.com/ianan/demreg/tree/master/python)

The two sswidl versions should give similar results but the mapping version will be quicker.
