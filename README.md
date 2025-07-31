# salesforce-google-sheets-zapier-integration


**Google Sheets to Salesforce Contact Integration via Zapier**
This mini-project demonstrates how to automate the creation of Salesforce Contact records using data entered into a Google Sheet — with **no code required**, powered by **Zapier**.
> :sparkles: A simple and practical automation that bridges Google Workspace and Salesforce CRM.
---
## :rocket: Project Overview
The goal of this project is to reduce manual data entry and streamline contact management by connecting Google Sheets and Salesforce using Zapier.
Whenever a new row is added in the Google Sheet (containing contact data), a new **Contact** record is automatically created in Salesforce.
---
## :wrench: Tools & Technologies
- **Salesforce CRM** – for managing contact records
- **Google Sheets** – for inputting contact data
- **Zapier** – for automation between the two platforms
- **REST APIs** – used by Zapier to communicate with Salesforce in the background
---
## :repeat: Workflow
1. **Google Sheet** is prepared with the following columns:
   - First Name
   - Last Name
   - Email
   - Phone Number
2. A **Zap** is created with two steps:
   - **Trigger**: New Spreadsheet Row in Google Sheets
   - **Action**: Create Record in Salesforce → Object: `Contact`
3. Once a new row is added to the sheet, Zapier sends the data to Salesforce.
4. A new Contact appears in Salesforce instantly.
---
## :bulb: Use Cases
- Allow non-Salesforce users (e.g. sales assistants, interns) to add contacts using a shared Google Sheet
- Quickly bulk import contacts without logging into Salesforce
- Real-time CRM updates from remote data entry points
---
