# Added by me

Check the tutorial in https://developers.sap.com/group.fiori-tools-odata-v4-incident.html

**Steps to run the app:**
Open command pallet and search "Application info". Then from there use preview app option.



## Description

This repository contains the sample OData V4 service material for the tutorials provided in the SAP Developer Center. On top of that I have added the Fiori Elements list and object page.

## Project status

**Current status**
- The project is running locally. Check the steps above to run the app.
- Able to deploy to BTP CF. There is no error during deployment. Able to load the app from SAP Build Work Zone.
- But the object page is not loading, if I click on a line item. My analysis: If I remove the custom fragment of the object page, then it is working. Check the below link:

https://community.sap.com/t5/technology-q-a/error-content-security-policy-failed-to-execute-module-factory-for-sap/qaq-p/13724272


**Next Steps:**
- Add Unit test
- Add new functionalities