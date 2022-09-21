# PowerShell Challenge #003 - Loopy Conditions

## Core Task

Create a script to check if a specific AppxBundle package is installed for each user on the machine.  If it is not, install it for all users.
NOTE: If you have access to the Windows Store for Business or similar repository, you can grab all the required files with an Offline applicaiton.  See https://nathanblasac.com/deploy-an-offline-client-app-with-intune-1253007f1e5d

## Advanced Task

Perform the Core Task but also check to see if there are any dependency Appx files included in your payload and append your install command to include each one found programatically.

## Expert Task

Perform the Advanced Task, but validate whether each dependency is already installed, and if it is do not append it to your install command.


