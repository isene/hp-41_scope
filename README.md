# hp-41_scope
## HP-41: Telescope and observational utility

This program calculates values for telescopes and oculars. You start the program, add a telescope and then as many oculars as you want. You can then view several values for the telescope as well as the details for each ocular when used with this telescope. You can also save the data set (telescope and oculars) to an XM file or retrieve a file saved earlier. You may add new oculars as needed to a retrieved file and save it anew.

Upon **XEQ "SCOPE"**, the program give you the following menu:

Label (Menu)	|Description
----------------|-----------
LBL A (+T)	|Add the telescope. You will be asked for the telescope name (max 6 characters), the Aperture in millimeters and the Focal Length in millimeters.
LBL a (,V)	|View the basic data for the telescope: F-ratio, Resolution limit (Dawes), Resolution limit (Rayleigh), Magnitude limit, Light gathering compared to the human eye, Lowest possible magnification, Highest possible magnification – and then the most suitable magnifications for: Starfields, Galaxies and nebulae, Planets/Moon and planetary nebulae and globular clusters, planetary details and double stars, tight double stars. If you have added any oculars, the program will then jump straight to LBL b and show the values for the oculars related to this telescope.
LBL B (+O)	|Add an ocular. You will be asked for the focal length in millimeters and the apparent field of view for the ocular.
LBL b (,V)	|View the basic data for the oculars as used with the telescope added via LBL A: Magnification, Actual field of view (degrees), Actual field of view (minutes), Exit pupil.
LBL C (G)	|Get data set. You will be asked for the name of an earlier data set.
LBL D (S)	|Save data set. An XM file will be created with the name of the telescope (as entered via LBL A).
LBL E	|Go back to the menu.
