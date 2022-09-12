# PowerShell Challenge #002 - Deploying Payloads

## Core Task

Download the ExamplePayload.zip and create a script to do the following:

1. Test if each file already exists in the Public Desktop folder
    - If they do not exist, copy the one from the ExamplePayload directory there (do not move them)
    - If they do exist, replace them with the new version
2. Validate all the target files have infact been updated from the payload.

## Advanced Task

1. Check to see if each user on the machine has these same files on their desktop
    - If they do, remove them so that the only place they exist is in the Public Desktop folder
2. Create a log of each action somewhere on the system for later review.

## Expert Task

1. Using only PowerShell, create a Scheduled Task to perform both the Core and Advanced Tasks daily as System.


