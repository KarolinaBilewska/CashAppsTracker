# CashAppsTracker
Application build in Power Platform. Power Apps Canvas application and Power Automate.

In order to import solution:
1. Create new SharePoint site
2. Using PnP.PowerShell invoke PnPSiteTemplate ("CashAppsTemplateSP.xml"). All required SharePoint lists and some dummy data will be created.
3. Import solution "CashAppsTracker_1_0_0_X.zip" to you environment. Select required Connections during import (ver 1.0.0.2 only uses Outlook 365 and SharePoint) as well required environment variables (ver 1.0.0.2 only uses SharePoint Site - please select SharePoint site created in (1) and SharePoint lists - please select appropriate SharePoint lists that were created in (2)
4. Feel free to go into EDIT mode and see my work
