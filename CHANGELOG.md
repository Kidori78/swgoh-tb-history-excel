# 2.2 #
- Removed the option to export the sheet to one tab. This option may come back in the future.

# 2.1 #
- Fixed Security issue where new workbook was trying to reference a cell in the main workbook.

# 2.0 #
Date: 1-26-2021
- Fixed Error with VLOOKUP trying to look at old workbook for values.
- Fixed Error with not generating Phase 5 and 6 when separating by phases.
- Added the following columns to each phase when separating by Phase:  Available GP, Deployed GP, Platoons Donated, Platoons Assigned, Rogue Actions, Combat Waves Completed, Exclusive Unit Mission Attempt, Exclusive Unit Mission Success.
- Added the following columns to each phase when putting it all on one tab: Platoons Donated, Rogue Actions, Combat Waves Completed, Exclusive Unit Mission Attempt, Exclusive Unit Mission Success.
- Added Territory Breakdown section at the bottom of Overview worksheet.
- NEW FEATURE: Added the ability to not auto export so the wb can be used during the event for tracking things. 
- NEW FEATURE: The wb can now load the csv obtained at the end of each phase in order to automatically calculate the following per phase: Combat Waves Completed, Platoons Donated, and Rogue Actions. These separated csv files can be ran individually or all at once.
- Added more settings to work with loading multiple csv files.

# 1.3 #
Date: 1-22-2021
- Added Mac compatibility. 

# 1.2 #
Date: 1-15-2021
- Fixed an error where files were not properly being moved.
- Adjusted Combat Mission headers to better indicate what they show numbers for.
- Fixed the Territory Battle IDs.

# 1.1 #
Date: 1-14-2021
- The main workbook will now auto-erase all data when it has finished creating the new workbook to eliminate any old data potentially getting copied with the new data.
