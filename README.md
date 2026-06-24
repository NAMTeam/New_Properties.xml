# New_Properties.xml

New_Properties.xml is the file that contains all the prorpeity definitions used in the exemplar and cohort files of SimCity 4. The file contains the algorithms for generating the statistics for the various lots

## Features

New_Properties.xml is an XML file that is used by the modding tools of PIM-X and ILives Reader in reading all propieties of SimCity 4 exemplars.  For this reason this file is essential in reading and creating the exemplar files

The file contains all the algorithms used to calculate building statistics (Residential, Commercial, Industrial, Civic and Utility) as well as generate TE (Transit Enable) switches and calculate station capacity. 

The file contains all the Occupant Groups that Maxis and BSC Team have developed allowing for better lot management. 

Because of the uniqueness of the file, new properties can be generated that the game can read using Mod DLLs and it also allows the identification of the IIDs of the prorpieties that can be used for any LUA codes to be used in the game.

## Advanced Features

Unlike the original New_Properrty.xml file, this version includes the following additional features and patches

- Public services (education, public safety, healthcare) have been completely overhauled, with a capacity increase four times that of the BSC version and twice that of the Maxis version, since the BSC version has values equal to half those of the Maxis version, forcing the player to build more civic buildings
- The educational buildings are compatible with the Education Realism Mod (ERM) and specific CAM, and they also add new buildings such as a kindergarten and a modular university.
- The utilities have been revised to include new types of power plants, electrical substations, and batteries, as well as to re-enable features removed by Maxis, such as the Freshwater Pump, Desalination Plant, and Incinerator.
- Transit-Enabled (TE) buildings comply with NAM-MTA specifications
- All additional properties created by the DLL Mods have been added
- Update all Occupant Groups (OG) by adding the recovered ones and the new ones
- Added Farm Files from SPAM and Colossus Farming, in addition to updating the BSC ones
- The park system has been revised and improved compared to the BSC & Maxis version
- Added additional buildings from the CAM expansions
- Additional buildings and properties from the CAM expansions have been added
- Ability to generate farms up to Stage 10 (Requires CAM or SPAM for Stages 4 and 5—Requires CAM for Stages 5 through 10)

This version of New_property.xml is the version that always contains the latest changes available compared to the original version, which will have delayed updates.

## Installation

The file must be installed by following precise instructions according to the program it is to read

### OLD PIM-X

New_Properties.xml should be installed in the PIM-X installation folder (generally the installation folder is this)`C:\Program Files (x86)\SC4PIM` replacing the original file. 


### NEW PIM-X

New_Properties.xml must be installed in the following folder `%APPDATA%\sc4pimx\`

### Ilives - Reader (1.5.4)

New_Properties.xml should be installed in the Reader installation folder `C:\Program Files (x86)\ILives\ILives Reader` replacing the original file. 


### Ilives - Reader (0.9.3)

This version of Reader does not use New_Properties.xml but tropod_Properties.xml. tropod_Properties.xml should be installed in the Reader installation folder (generally the installation folder is this) `C:\Program Files (x86)\ILives\ilive_reader093` replacing the original file. 
