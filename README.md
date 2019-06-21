# iCal Generator

Converts a csv file into an iCal .ics file ready to be imported into an Outlook Calendar for example. 

[Live Demo]:(https://timrose.me/ical-generator/)

## Getting Started

Format the CSV file in a certain way for it to be parsed correctly. 

### Headers

The file should contain the following headers in any order: 

* Subject
* Start Date
* Start Time
* Date Stamp
* End Date
* End Time
* All Day
* Description
* Location
* UID
* Busy Status

Note that the header must be written exactaly as shown above.

### Busy Status

_Busy Status_ can use the following keywords:

* FREE
* WORKINGELSEWHERE
* TENTATIVE
* BUSY
* AWAY

Note that the keywords must also be written exactaly as shown above.
