# xsoar-demisto-scripts

Working for a little time as a DEVOps on Palo Alto Networks XSOAR (aka Demisto), here are a few scripts that I had to create which helped my with some tasks.

## get_roles.yml
A little python script to get the role of a user. I've used this when creating conditional tasks checking if the agent was a Level 1 or Level 2 support.


## ReopenIncidents.yml
A little script which uses the rest API of Demisto to reopen a case as there is no built in command by default for this.

## FindingKeywordinList.yml
A little python script to lookup in a list (given as argument) some keyword. 

## Clear_notes.yml
A little python script which loops through all the incident ID entries and checks if they are highlighed Notes, and then unpublish them. Usefull when writing ReRun playbook types. 

## Clear_notes_evidences.yml
A little python script which loops through all the incident ID entries and checks if they are highlighed Notes, and then unpublish them. Usefull when writing ReRun playbook types.
And it clears all the evidences of an Incident ID using the Demisto API Rest (only way)

## jarm.yml
jarm.py from https://github.com/salesforce/jarm but adapted for XSOAR

## jarm_lookup.yml
A small automation with some known JARM fingerprints

see jarm.jpg to see how to use it


