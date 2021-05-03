# NYPD Misconduct Complaint Database – 08.20.20

**A previous version of the raw CCRB database file contained formatting errors that resulted in missing information. In the columns labeled “NYPD Disposition” and “Penalty Desc,” there were about 120 cells where data should have appeared yet the spreadsheet showed a blank value. If you downloaded the raw data before 12:00pm EST August 21, 2020, please download the corrected file that appears on the GitHub page now.**

`ccrb_database_raw.xlsx` is a record of the complaints made by the public to the Civilian Complaint Review Board (CCRB). These complaints span two distinct periods: the time since the CCRB started operating as an independent city agency outside the NYPD in 1994 and the prior period when the CCRB operated within the NYPD. The data includes 323,911 unique complaint records involving 81,550 active or former NYPD officers. The data does not include pending complaints for which the CCRB has not completed an investigation as of July 2020.

Using the CCRB complaint history data, which the NYCLU obtained through a Freedom of Information Law (FOIL) request, the NYCLU built a search tool to make the information more accessible: [nyclu.org/nypdrecords](https://nyclu.org/nypdrecords). Each row of the database represents a unique complaint made against an NYPD officer, including the officer’s name, current rank, and current command (the NYPD unit where the officer was most recently assigned, which may have changed since the complaint was filed). It is not uncommon for a single police-civilian encounter to result in multiple complaints against the same officer or against multiple officers. 

About 19,000 complaints, most of which were filed before 2000, contain some identical allegations. Some of these entries may be duplicates in the data the CCRB produced, though the NYCLU does not have a way to confirm that. About 33,000 entries list officer information, but contain NULL values for the complaint fields. The NYCLU cannot confirm the reason for the missing information. For more information, please visit [nyclu.org/nypdrecords](https://nyclu.org/nypdrecords)

`ccrb_database_raw.csv` is a .csv version of `ccrb_database_raw.xlsx`.

`ccrb_filespecs.xlsx` is a spreadsheet containing

1. information about each variable in `ccrb_database_raw.xlsx`
2. information clarifying some of the abbreviations used in the database
3. all differences between the raw data file and the version that is accessible through the interactive tool.

In the coming weeks we will update this file with additional details. For more information, please visit [nyclu.org/nypdrecords](https://nyclu.org/nypdrecords)
