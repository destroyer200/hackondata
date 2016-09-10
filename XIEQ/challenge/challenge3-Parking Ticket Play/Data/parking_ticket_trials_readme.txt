Release notes
=============
1. A new data set will be prepared each Friday evening after 8:00 pm and
   made available by the next day. This would allow one to inquire about 
   next week's parking ticket trial schedule, or weeks after that if available.

2. To check the schedule for a particular parking ticket, one may search the file
   using the last five (5) digits of the parking ticket number. This may result in
   multiple matches. The one with the offence date matching the ticket and the 
   first three (3) characters of the name of the vehicle owner, should be the one. 

3. The Notice of Trial is the official notification to defendents. In the event
   of a discrepancy between this dataset and the Notice of Trial, the Notice of 
   Trial shall prevail.

4. The data set released is in a compressed format (.zip) and contains up to 20 
   Comma-Separated Values (.csv) files. This represents the current schedule and 
   past 19 weeks' for comparison purposes. The files can be opened by a spreadsheet
   program or any text editor.

5. Court Services is responsible for scheduling up-coming parking ticket trials.
   The number of trials contained in a file may grow from one week to the next
   due to Court Services scheduled more trials during the week.

6. A parking ticket may appear on the schedule and disappear from the next
   if the ticket was paid at least two (2) business days prior to the trial date.

7. The City of Toronto reserves the right to change the details above any time
   without notice.

Attributes:
=============
COURT_DATE - Date YYYY-MM-DD
COURT_LOCATION - String up to 30 characters
COURT_ROOM - String up to 4 characters
COURT_TIME - Numeric HHMM 24 hour clock
PARKING_TICKET_NUMBER - String first 3 characters are masked by asterisks
INFRACTION_DATE - Date YYYY-MM-DD
FIRST_3_LETTERS_NAME - String up to 3 characters of vehicle owner last name/company name


