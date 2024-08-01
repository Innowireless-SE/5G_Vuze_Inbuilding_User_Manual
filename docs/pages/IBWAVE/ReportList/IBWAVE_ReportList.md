# IBWAVE Mode

## Report List

Report List section displays detailed information of each report, monitors status of report file publication and manually publishes and downloads report file.

<p align="center">
  <img src="https://github.com/Innowireless-SE/5G_Vuze_Inbuilding_User_Manual/blob/master/docs/images/IBWAVE/3-1-1.png?raw=true">
</p>

#### Report Status

Report publication status is shown in bar graphs. 
Total and Daily Report Status is shown if mouse- over the total and daily report in bar graph. 

- Green – Complete, Red – Fail, Navy (Default) – Waiting


<figure markdown="span">
  ![Image title](https://github.com/Innowireless-SE/5G_Vuze_Inbuilding_User_Manual/blob/master/docs/images/IBWAVE/3-1-2.png?raw=true/600x400/){ width="400"  }
  <figcaption></figcaption>
</figure>

- a.	Total : Sum of all reports that have been published up to now.
- b.	Daily : Initial screen displays report publication statistics of today. When searching based on date, report statistics on the date is displayed.


#### Searching Report

Reports are searched by Date, SAP ID, Building or Circle 
Options for displaying the report include filtering by date and displaying the entire report. Select the radio button to see reports by date or the entire report. the filtered reports are listed up in Report List.

1. Select whether to view reports by date or the entire report
    - a.	If you are looking at data by date, click radio button(red)
    - b.	If you want to see the entire data, click radio button (blue)
<figure markdown="span">
  ![Image title](https://github.com/Innowireless-SE/5G_Vuze_Inbuilding_User_Manual/blob/master/docs/images/IBWAVE/3-1-3.png?raw=true/600x400/){ width="500"  }
  <figcaption></figcaption>
</figure>
2. To search report by date
    - a.	Configure date in calendar or using left and right date buttons. 
    - b.	Dates with data are marked in red in calendar(green).
<figure markdown="span">
  ![Image title](https://github.com/Innowireless-SE/5G_Vuze_Inbuilding_User_Manual/blob/master/docs/images/IBWAVE/3-1-4.png?raw=true/600x400/){ width="500"  }
  <figcaption></figcaption>
</figure>

3. To search entire report 
     - a.	Select ‘All Dates’ radio button.
<figure markdown="span">
  ![Image title](https://github.com/Innowireless-SE/5G_Vuze_Inbuilding_User_Manual/blob/master/docs/images/IBWAVE/3-1-5.png?raw=true/600x400/){ width="500"  }
  <figcaption></figcaption>
</figure>
4. To search report by SAP_ID, Building, or Circle.
    - a.	After selecting whether to view the report by date or the entire report,
      User can search by searching for the name of SAP_ID, Building, or Circle.
    - b.	Click on SAP_ID dropdown list, select SAP_ID, Building or Circle.
    - c.	Click on search button to find report of specific SAP ID, Building or Circle.
    - d.	For searches, User can enter only part of the name, instead of entering the full name.
      Ex) SAP ID Name : I-MU-MUMB-ISC-0658 (searching like ‘0658’ possible)
<figure markdown="span">
  ![Image title](https://github.com/Innowireless-SE/5G_Vuze_Inbuilding_User_Manual/blob/master/docs/images/IBWAVE/3-1-6.png?raw=true/600x400/){ width="500"  }
  <figcaption></figcaption>
</figure>


#### Report List Table

Searched reports are listed up in Report List table. SAP ID columns are shown in different colors in accordance with test result of the report.

Report files are downloaded and issued in Report List table.

<p align="center">
  <img src="https://github.com/Innowireless-SE/5G_Vuze_Inbuilding_User_Manual/blob/master/docs/images/IBWAVE/3-1-7.png?raw=true">
</p>

- SAP ID : SAP ID name showing in different colors in accordance with report publication status. (Green – Complete, Red – FailNavy (Default) – Waiting)
Measurement test regions are categorized by SAP ID.
- Building : Display test Building Name
- Circle : Display test Circle
- Info : Displays Test Building Info, SAP ID, Building name, Address, Position, Building type, Top floor, Bottom floor, Measured, Height, Number of Small Cell, Frequency Band, File count, IBWAVE file update time and Modified time.
- Cycle : Number of measurement test cycle conducted for the IBWAVE mode.
- Band : Display test frequency band.
- File Cnt : Number of log file in total
- No of Floor : Total number of floors in the building
- Measured Floor : Number of measured floors in the building
- Upload Status : Display the report measurement status, and if the report is created for all floors, it becomes 'Complete', otherwise it is displayed as Waiting.
- Report : Display the entire floor-by-floor measurement status of the corresponding SAP ID. Also, if a report is generated for even one floor, User can download the report through the Pass, Fail or In-Progress button.

- Doc : Reprocesses files that have been processed.
Download : The analysis documents created in *.xls and *.ppt separately can be uploaded and downloaded for each Cluster. [Doc] column shows file format type if there are uploaded analysis documents. Download the uploaded analysis documents for corresponding Cluster.



