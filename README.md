# New_Properties.xml

New_Properties.xml is the file that contains all the prorpeity definitions used in the exemplar and cohort files of SimCity 4. The file contains the algorithms for generating the statistics for the various lots

## Features

New_Properties.xml is an XML file that is used by the modding tools of PIM-X and ILives Reader in reading all propieties of SimCity 4 exemplars.  For this reason this file is essential in reading and creating the exemplar files

The file contains all the algorithms used to calculate building statistics (Residential, Commercial, Industrial, Civic and Utility) as well as generate TE (Transit Enable) switches and calculate station capacity. 

The file contains all the Occupant Groups that Maxis and BSC Team have developed allowing for better lot management. 

Because of the uniqueness of the file, new properties can be generated that the game can read using Mod DLLs and it also allows the identification of the IIDs of the prorpieties that can be used for any LUA codes to be used in the game.

## Installation

The file must be installed by following precise instructions according to the program it is to read

### PIM-X

New_Properties.xml should be installed in the PIM-X installation folder `C:\Program Files (x86)\SC4PIM` replacing the original file. 
