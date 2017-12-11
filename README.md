 ## :exclamation: Notice
 This script is outdated. Please look at next version https://github.com/dubravcik/pbixrefresher-python

# PBIXRefresher
Powershell tool to refresh Power BI (*.pbix) workbooks

## Dependencies
Script require UIAutomation libraries to work with GUI of Power BI Desktop interface.

## Usage
refresher.ps1 -workbook NameOfWorkbook.pbix [-publish]

Parameters:
- workbook - filename of PBIX workbook
- publish - switch to publish the workbook, if not passed the workbook is only refreshed and saved locally (useful if OneDrive is used)


