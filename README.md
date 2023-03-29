# Stellar_Classification
An exploration of a set 100,000 observations of stars, galaxies, and quasars done by the Sloan Digital Sky Survey

This project analyzes some distinct characteristics of three types of stellar objects (galaxies, stars, and quasars). Particular attention is paid to location, redshift, and ultraviolet radiation, with the bulk of the results focusing on the relationship between redshift and ultraviolet radiation for observed quasars.

Below is a key of each characteristic in the data set to be used for reference. A handy dictionary is also included in the Jupyter Notebook and any definition can be called using data_key['desired_characteristic'] 

Follow along by loading the data [here](https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17?resource=download)

# Key 
* obj_ID = Object Identifier, the unique value that identifies the object in the image catalog used by the CAS
* alpha = Right Ascension angle (at J2000 epoch)
* delta = Declination angle (at J2000 epoch)
* u = Ultraviolet filter in the photometric system
* g = Green filter in the photometric system
* r = Red filter in the photometric system
* i = Near Infrared filter in the photometric system
* z = Infrared filter in the photometric system
* run_ID = Run Number used to identify the specific scan
* rereun_ID = Rerun Number to specify how the image was processed
* cam_col = Camera column to identify the scanline within the run
* field_ID = Field number to identify each field
* spec_obj_ID = Unique ID used for optical spectroscopic objects (this means that 2 different observations with the same spec_obj_ID must share the output class)
* class = object class (galaxy, star or quasar object)
* redshift = redshift value based on the increase in wavelength
* plate = plate ID, identifies each plate in SDSS
* MJD = Modified Julian Date, used to indicate when a given piece of SDSS data was taken
* fiber_ID = fiber ID that identifies the fiber that pointed the light at the focal plane in each observation


## Project Fullfillments for Code Louisville Data Analytics I
Here is how I incorporated the requirements for this project:

* Part 1: "Read data in"
  - Used the Pandas read_functions to read in my csv file from the domain [here](https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17?resource=download)
  
