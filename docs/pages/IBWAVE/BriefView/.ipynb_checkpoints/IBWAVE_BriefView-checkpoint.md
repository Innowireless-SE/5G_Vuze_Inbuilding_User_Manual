# Breif View 

Brief View section is displaying detailed and summarized data under statistical tabs of Summary, KPI Result, Event List, File List.

## Summary

### 1. Floor plan 

In Floor Info, User can get information about reports for each floor of the selected SAP_ID, log reprocess, issue reports, download reports.

<p align="center">
  <img src="https://github.com/Innowireless-SE/5G_Vuze_Inbuilding_User_Manual/blob/master/docs/images/IBWAVE/3-3-1.png?raw=true">
</p>


#### Floor 	
Measured floor. 

#### Freq.Band	
Test Frequency Band.

#### No.of Small Cell   	
The number of Small Cell


#### Upload Status	
Displaying floor Report Status 
- When all files are uploaded, the column is shown as [Complete].
- When all files are not uploaded completely, the column is shown as [Waiting].

####  Report 
- Button is activated only when report is published. In case there is published report :
- When the test result in Report is [Pass], the column shows [Pass] button to download. When the test result in Report is [Fail], the column shows [Fail] button to download. While re-publishing report by using [Re-process] button, the column shows [Reprocessing].
- In case there is no published report :
        - The column shows in blank. When errors are happened during file converting, [error] is shown. When trying to publish report by force by using [Issue] button, the column shows [Issuing].
- When this button is in Waiting or Issuing status, user can click the button to see the Report Waiting List. It shows current list of reports that are waiting to be issued.


#### Publish Report
- [Issue] button appears to publish report manually with updated cellref, BSP, drive test route, and cluster boundary information.
- User can decide whether to process new report nad sent to Siteforge or process only the report. This option is only available when file list is complete.
- [Issue] button disappears while publishing report and compiling DB for Map analysis after clicking [Issue] button.
- This function is only available to admin and team manager account.

- Re-process	Reprocesses the selected log files. Report can be re-published with the reprocessed measurement file.

- [Report Information]	Displays the report information of the selected SAP ID. Shows the report status, Band, number of log files for each scenario, and report creation time.
<figure markdown="span">
  ![Image title](https://github.com/Innowireless-SE/5G_Vuze_Inbuilding_User_Manual/blob/master/docs/images/IBWAVE/3-3-2.png?raw=true/600x400/){width="500"  }
  <figcaption></figcaption>
</figure>


 
- [Re-Process All]	Reprocesses All log files.




### 2. RF Info 

RF Info shows the 5% and 95% median RF values for the corresponding floor's RSRP, RSRQ, SINR, DL MAC Throughput, UL MAC Throughput, and Tx Power values.


<p align="center">
  <img src="https://github.com/Innowireless-SE/5G_Vuze_Inbuilding_User_Manual/blob/master/docs/images/IBWAVE/3-3-3.png?raw=true">
</p>

## KPI Result

KPI Result tab displays KPI information of report selected in Report List in table and displays the Target Value  and the results of all floors at once.

<p align="center">
  <img src="https://github.com/Innowireless-SE/5G_Vuze_Inbuilding_User_Manual/blob/master/docs/images/IBWAVE/3-3-4.png?raw=true">
</p>

## Event List 

Event List tab displays all call events encountered during IBWAVE Mode test. The call events including event can be filtered in table by clicking Filter icon of Event Name.


####  Floor  	
Floor where the event occurred
####  Issued Time   	
Event time when the event occurred
####  Event name	 
Display event name. To filter and display particular event names only, click. Filter icon and select the checkboxes of desired event names.
####  Scenario 
Display scenario name applied for the log file.
####  PCI	 
Display PCI where the event occurred.
####  RSRP	
Display SINR at the location where the event occurred.
####  SINR	 
Display RSRP at the location where the event occurred.
####  Analysis	 
Process detailed analysis for the event in a separate screen. Button names shows detail analysis status.

- When clicking [Ready] button, detail analysis is started to process displaying [In Prog] button, and the button is turned to [View] when it is completed.
- [View] button opens Detail Analysis screen, and processes detailed analysis of log file.
- [Ready]: Standing by for detail analysis.
- [In prog]: Processing detail analysis is in progress.
- [View]- Processed detailed analysis information is monitored in separate screen. For details of detailed analysis in a separate screen, see Detail Analysis.
- [Error]- Error happened during processing detailed analysis. Click Error
- button and detailed analysis will be processing again.
####  Log File	
Display size and name of log file which includes the call event. Download button downloads the log file.
####  [Export]	 
Export the event list in *.xls format.
####  [Refresh]	 
Reset analysis button from View to Ready to allow re-converting of the detailed analysis.




## File List

#### Floor	 
Floor where the event occurred
#### Uploaded Time	 
Display the time the log file was uploaded to the server.
#### Mobile ID	
Display Mobile ID of the log file.
#### Sequence	
Display sequential number.
#### Scenario	
Display scenario name applied for the log file.
#### Band	 
Display frequency band of the log file
#### Status	 
Display the status of the log file.

1.	`Complete` : File converting is complete.
2.	`Error` : Converting error.
#### Number of event	 
Display number of events encountered in the log file.
#### Log File	
Display size of log file. Click `Download` button to download drx log file. Many log files in the list can be downloaded at once by selecting all log file user wants to download and clicking `Download Log Files` button in the top right corner.
#### [Reprocess]	 
Reprocesses all listed files. Report can be re-published with the reprocessed measurement file.
#### [Download]	 
Download selected log files in the File List at once.
#### [Export]	 
Export log file information in .xlsx format
 
- `Refresh`	- Refresh the data in File List. 
- `Delete`	- Delete selected log files. (Admin Only)




