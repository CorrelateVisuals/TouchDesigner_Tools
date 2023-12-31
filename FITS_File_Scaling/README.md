# FITS File Scaling

![Image](https://github.com/CorrelateVisuals/Touchdesigner_Tools/blob/main/FITS_File_Scaling/FITS_File_Scaling_Image.PNG?raw=true)

A ![FITS](https://fits.gsfc.nasa.gov/fits_standard.html) (Flexible Image Transport System) file is a standard format used in astronomy for storing images, tables, and other data. It is designed to be platform-independent and widely supported by astronomical software for data analysis and sharing.

Image used for this example:
```
COMMENT      *****FINAL REDUCTION BLOCK*****
FILE-NAME    'FINAL_EMIR_STR_IMG_H.fits'
INSTRUMENT   'EMIR    '               / EMIR
DATE-OBS     '2017-08-13T22:38:38.81' / Date of observation (start) in Y2K complian
UTC          '22:38:38.814872'        / Coordinate UT of the observation (start)
COMMENT      *****EXPOSURE BLOCK*****
READMODE     'CDS     '               / Detector readout mode in string
EXPTIME      4.999289 / [s] Exposure time
SECTIME      6.054519 / [s] Total time per sequence
```
Based on data from the GTC Archive at CAB (CSIC -INTA).The GTC Archive is part of the Spanish Virtual Observatory project funded by MCIN/AEI/10.13039/501100011033 through grant PID2020-112949GB-I00. Astronomical data stored in FITS format can be attained at ![GRANTECAN's database](https://gtc.sdc.cab.inta-csic.es/gtc/index.jsp). For more information visit ![GRANTECAN](http://www.gtc.iac.es/).

Special thanks to ![Derrivative](derivative.ca/) for implementing this widely adopted format into TouchdDesigner and assisting with the mathematical calculations.
