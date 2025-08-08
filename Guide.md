# Street Works Sentinel Suite Guide

This guide will provide you with the basics for using each aspect of the Street Works Sentinel Suite of programs.

## General Setup

 - Download the Sentinel Suite zip file in the releases section of this
   GitHub repository. 
 - Extract/Copy out all of the files from inside the
   zip file, in the same structure (copy and paste as is) to a new
   location on your computer/network.
 - Run Launcher.exe

## FPN Sentinel

You will need a Street Manager Download All My Data (DAMD) zip file to process. FPN Sentinel will process whatever you provide, but for sanity, I would suggest a week or two of data.
Geoplace API Integration: For S70 Distance checks, you will need a Geoplace DataVIA API login.  Please contact Geoplace to assist with this. 

 - Launch FPN Sentinel from the Launcher.
 - Press the "Select and Extract DAMD Zip" button.
 - Locate your Download All My Data Zip file and click OK.
 - Should you wish to perform a S70 Distance check, check the checkbox and add your API login details under "File" > "Set API Credentials" > "Save".
 - The output will display the date range of your selected file. If you are happy with this, press "RUN ANALYSIS".

The output will display a summary of the possible FPNs in the data provided.  To look at each section go to the "Results" drop down menu and select the contravention list.
Should you wish to view a particular works further, or issue an FPN, double click on the works in the list.  This will direct you to the Street Manager works page for that particular works reference.

## TPI Sentinel

TPI Sentinel requires 3 data Extracts from Street Manager, a "Works" extract, a "FPN" extract and a "Reinstatement" extract.  These can be gather from the appropriate section of Street Manager, filter the dates (Suggest minimum of 1 year, April to March), and scroll to the bottom of the page and press "Extract".

If you have multiple large extracts in a folder, you can select the "Auto-Detect file from folder" button and direct to the folder containing these extracts, the program will determine the most recent and use that data.

Should you wish to manually select the data extracts you can press on the appropriate button and direct to the file location.

Please set your reporting period.  This should cover the period you data extract covers, or be a smaller range than the data extracted.  

Press "Generate TPI Report".

This will provide a summary of the report data, which can be extracted should you wish by going to "File" > "Export" > "Export Summary to CSV".

Should you wish to view graphs on each TPI, navigate to the "Reporting" menu and select the appropriate TPI.


## Management Sentinel

Management Sentinel will require a Download All My Data (DAMD) zip file(s) from Street Manager.  This can be of any duration, (a minimum of a month is suggested), and multiple files can be selected.  To select multiple files, e.g. several monthly extracts, place all the DAMD extracts in one folder and press the "Load Download All My Data Folder(s)" button.  Select the appropriate folder with your downloads.

Next go to "File" and "Set Activity Filters", this section can be used to select Authority/Utility user actions and also determine the domain of the users to display.  Set "Filter by User Domain" to your Highway Authority/Company Street Manager login domain, such as @Council.gov.uk (include the @) and press "Add" then "Save and Close".

Your display will now update with the new filters.

Usernames in the list can be double clicked to see a more detailed breakdown of user activity.
*Note: Should you only have one user visible, this may indicate you primarily use an API to manage Street/Road Works, as such, only the API users activity will be visible.*

Works/FPN/Inspection Analysis 
Select a "Start" and "End" range and then click "Apply Filter". Each bar chart column can be clicked for a more detailed report on that aspect.
