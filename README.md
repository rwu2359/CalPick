# CalPick Range version
Card Window date-range picker for FileMaker solutions<br />
![Screenshot](https://cloud.githubusercontent.com/assets/779522/26669512/12c81756-46a6-11e7-9609-f17b6736fb33.jpg)

## Required
FileMaker Pro 16 or above

## Installation
Download both FMP12 files, open Card-Cal_2 and look at the read-me script
The Card-Cal_2 has been cloned, and should run a script op open to populate a single record which should bind the dates to your system. Thanks to @JasonYoung for reminder on that one.

## Hosting
The CardDatePickerRange file can be hosted so it can be available to all you solutions if required, make sure you edit scripts as outlined in the read-me

## Running
See example scripts in Card-Cal_2 file<br />
Has some beauty on iOS as the layout doesn't move like when using the native picker<br />
Not available on WebDirect!
There are some extra JSON parameters for the range version which will go straight to the end date panel once a start date is selected, and one to auto-close on selection of the end date. Read. The. Read-me.

## Hacking the design
The files are open and unlocked, instructions about styling are in the read-me<br />
The rounded corners are a trick which will not work so well on a different colour header, I leave you to figure it out and amend or remove as required<br />
I recommend using this to get used to the new Layout Objects inspector panel

## Issues
Please use the issues tab to report any issues you may find

#### version history
1.0 2017-05-31, initial release<br />
1.1 2017-05-31, amended method of passing selected date, thanks to @ToddGeist, fixes #1
1.2 2017-09-01 - fixed script name type, fixes #4
1.3 2017-10-09 - more explicit handling for cancel and picker errors, first release of range picker
