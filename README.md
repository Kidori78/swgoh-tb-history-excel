# SWGoH Territory Battle History - Excel Workbook
An Excel Workbook for Windows and Mac that takes the csv file created by Hotbot's tbstats command and automatically converts it into an Excel Workbook for archiving, reviewing and tracking purposes. It offers several settings for customizing including where the new Workbook will go, what to name it, and what to do with the tbstats file after the conversion. These options can enable this workbook to be a one click solution to easily format and gerenate a new workbook with only the specified information in the appropriate Territory Battle folder with the proper file name to easily archive it for future reference.

## Getting Started ##
Download the latest version of the Excel Workbook to your computer and place it into the directory where you want to have folders created to archive the history of your guild's Territory Battles. Add the tbstats file to the same folder that this workbook is in and make sure the file name matches the File name in the Settings worksheet. 

The first time you open the workbook it will let you know that macros are disabled, you will need to enable macros in order for this workbook to function. After enabling macros adjust the values in settings how you would like them and press Alt + F8 and choose Import_TB_History.

## Adjusting Settings ##
### Use form for operations ###
This setting will enable a form that can be used to perform all operations with the workbook.<br />
The default is set to TRUE.
### Auto close when finished ###
This setting will close the workbook when it is done converting the csv file(s).<br />
The default is set to FALSE
### Delete/Move Import File ###
These options will either move the tbstats.csv file to the specified folder or it can be deleted.<br />
The default for Delete is set to FALSE and the default for Move is set to TRUE.
### File name ###
This option lets people specify the tbstats csv file name the program will look for.<br />
Default is tbstats.csv
### Move folder name ###
This option specifies and can create the folder to archive the tbstats.csv file to.<br />
The default is set to TBSTATS Files
### Territory Battle IDs ###
These should not be adjusted and are used specifically for identifying which Territory Battle the tbstats file goes to. It uses the id specified in the games code for each Territory Battle.
### TB Folder Names/TB Save Names ###
These options specify the file name used for the exported workbook to be archived and the folder name it will go in. These settings must be changed as a pair and should only be done using the Form.
### Auto Export ###
This setting will turn off auto exporting the current csv information to a new workbook. This option is good for players that want to use it for tracking purposes or review while the Territory Battle is live. This setting is specifically used with Load CSV by phases setting, but technically will work for formatting any csv file. Players choosing this option will have to use Alt + F8 and choose Manual_Export in order to archive the project.<br />
The default is set to TRUE.
### Load CSV by phases ###
This setting will allow players to upload a csv file for each phase of the Territory Battle. Choosing to do this allows for the tables to capture more data automatically such as, Combat Waves Completed, Platoons Donated, and Rogue Actions per phase.<br />
The default is set to FALSE.
### CSV file name Phases ###
These options allow people to specify different names for the csv files used for phases.
### Current TB Loaded ###
This setting should not be manually adjusted and is used by the program to determine manual exporting infromation.
### Use api to get gp ###
COMING SOON
### API Login/Password ###
COMING SOON

## Release Notes ##
View the [changelog](/CHANGELOG.md) to see version updates.

## About ##
Author: Kidori<br />
Discord: https://discord.gg/pUWPaVhE2E<br />
License: MIT

## CREDITS ##
Uses VBA-Web and Dictionary classes created by Tim Hall.<br />
HotBot and HotUtils created by HotSauce.
