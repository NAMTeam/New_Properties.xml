# New_Properties.xml

New_Properties.xml is the file that contains all the prorpeity definitions used in the exemplar and cohort files of SimCity 4. The file contains the algorithms for generating the statistics for the various lots

## Features

New_Properties.xml is an XML file that is used by the modding tools of PIM-X and ILives Reader in reading all propieties of SimCity 4 exemplars.  For this reason this file is essential in reading and creating the exemplar files

The file contains all the algorithms used to calculate building statistics (Residential, Commercial, Industrial, Civic and Utility) as well as generate TE (Transit Enable) switches and calculate station capacity. 

The file contains all the Occupant Groups that Maxis and BSC Team have developed allowing for better lot management. 

Because of the uniqueness of the file, new properties can be generated that the game can read using Mod DLLs and it also allows the identification of the IIDs of the prorpieties that can be used for any LUA codes to be used in the game.

## Differences from the New_Properties.xml-patches version

This version does not include many of the advanced features found in the [New_Properties.xml-patches](https://github.com/UlisseWolf/New_Properties.xml-patches "New_Properties.xml-patches") version, which updates more quickly and is more compatible with CAM, CAM-SPAM, and CAM-Vanilla.

The main differences are

- Public services (Education, Healthcare, Safety) have values that are half those of Maxis, forcing the player to build more civic buildings in line with the BSC Team vision. The New_Properties.xml-patches version has values four times those of the BSC Team and twice those of Maxis.
- Delay in updating this version with new buildings and patches compared to the New_Properties.xml-patches version

We strongly recommend choosing the right version for your modding project. As a general rule, 

- New_Property.xml -> Recommended for a vanilla or hybrid vanilla experience
- New_Properties.xml-patches -> Recommended for a CAM experience (CAM, CAM-SPAM, and CAM-Vanilla) or a hybrid experience

## Installation

The file must be installed by following precise instructions according to the program it is to read

### OLD PIM-X (Note: The old PIM-X is being phased out. We recommend using the new PIM-X.)

New_Properties.xml should be installed in the PIM-X installation folder (generally the installation folder is this)`C:\Program Files (x86)\SC4PIM` replacing the original file. 

### NEW PIM-X

New_Properties.xml must be installed in the following folder `%APPDATA%\sc4pimx\`

### Ilives - Reader (1.5.4)

New_Properties.xml should be installed in the Reader installation folder `C:\Program Files (x86)\ILives\ILives Reader` replacing the original file. 


### Ilives - Reader (0.9.3)

This version of Reader does not use New_Properties.xml but tropod_Properties.xml. tropod_Properties.xml should be installed in the Reader installation folder (generally the installation folder is this) `C:\Program Files (x86)\ILives\ilive_reader093` replacing the original file. 
