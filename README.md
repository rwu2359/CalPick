# CalPick Range version
Card Window date-range picker for FileMaker solutions<br />
![Screenshot](https://user-images.githubusercontent.com/779522/34734526-f42394f2-f563-11e7-8eaa-3bb7429e29b6.jpg)

## Required
FileMaker Pro 16 or above

## Installation
Download both FMP12 files, open Card-Cal_2 and look at the read-me script
The Card-Cal_2 has been cloned, and should run a script On Open to populate a single record which should bind the dates to your system. Thanks to @JasonYoung for reminder on that one.

## Hosting
The CardDatePickerRange file can be hosted so it can be available to all you solutions if required, make sure you edit scripts as outlined in the read-me

## Running
See example scripts in Card-Cal_2 file, bottom button triggers refreshObject parameter<br />
Has some beauty on iOS as the layout doesn't move like when using the native picker. Not available on WebDirect!<br />
There are some extra JSON parameters for the range version which will go straight to the end date panel once a start date is selected, and one to auto-close on selection of the end date. Read. The. Read-me.

## Hacking the design
The files are open and unlocked, instructions about styling are in the read-me<br />
The rounded corners are a trick which will not work so well on a different colour header, I leave you to figure it out and amend or remove as required<br />
I recommend using this to get used to the new Layout Objects inspector panel

## Issues
Please use the issues tab to report any issues you may find

#### version history
1.0 2017-05-31 - initial release<br />
1.1 2017-05-31 - amended method of passing selected date, thanks to @ToddGeist, fixes #1<br />
1.2 2017-09-01 - fixed script name type, fixes #4<br />
1.3 2017-10-09 - more explicit handling for cancel and picker errors, first release of range picker<br />
2.4 2017-12-05 - added parameter to use in display mode only<br />
2.6 2018-01-09 - added parameter to show bank holidays or lockout dates
2.7 2018-07-03 - added parameter to refresh an object on date return
