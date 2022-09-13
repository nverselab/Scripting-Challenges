# PowerShell Challenge #003 - Loopy Conditions

## Core Task

Create an array of all the folder and files names in the current user's home directory and loop through each one until you find one with the word "Microsoft" or "Edge" in the name then: 
- Display the number objects checked before you found one
- Display the full path of the file or folder found
- Display the Date Modified of the file or folder found

## Advanced Task

Create an array of all the folder and file names in the current user's home directory and loop through each one then:
- Display the number objects containing the .lnk, .url, or .json file extension
- Ask the user to specify a directory path to save the export, but only let them continue if they provide a valid path in their home directory
- Export a list of filepaths and Date Modified for each of the files found to the directory provided by the user

## Expert Task

Complete the same Challenge as the Advanced Task, but also:
- Tell the user they only have 5 opportunities to provide a valid path in their home directory and display the number of tries remaining after each attempt
- After their 5th invalid attempt, export the list of filepaths and Date Modified for each of the files found to their Desktop instead


