# 📧 Constant Contact Integration for Salesforce
## 📊✨ Summary:
This Salesforce integration enables seamless data flow between Salesforce and Constant Contact, allowing for automated event and event registration management. With this solution, users can synchronize event lists and registrant information directly from Salesforce to Constant Contact, maintaining an active connection. Automated token management ensures uninterrupted data updates.

## 🛠️ Features
* **Automated Token Management**: Refreshes access tokens every 24 hours to ensure continuous connectivity.
* **Event List Synchronization**: Automatically creates Constant Contact event lists based on Salesforce event data.
* **Registrant Management**: Adds and updates event registrants as contacts within Constant Contact, directly from Salesforce.
* **API Request Handling**: Implements secure OAuth 2.0 token handling, with dynamic refresh capability using Named Credentials.

## ⚙️ Setup Guide
**Prerequisites**: 
1. Complete steps 1 & 2 per the [API Docs – Quick Start Guide](https://v3.developer.constantcontact.com/api_guide/getting_started.html)
2. Choose "**Authorization Code Flow and Implicit Flow**" for the OAuth2 setting this application will use to authenticate.
3. Choose "**Long Lived Refresh Tokens**" for the tocken refresh method.
4. Install the "**Constant Contact Integration Suite for Salesforce**" unmanaged package in your Salesforce developer org. If you don't have developer org, you can sign up for a 
   free developer org here: [Sign up for your Salesforce Developer Edition](https://developer.salesforce.com/signup). After successfully installing the package, all the included 
   metadata types.
   
## 📦 Package Metadata Components
1. **Apex Classs**:
2. **Apex Triggers**:
3. **Custom Objects**:
4. **Custom Tabs**

## 📝 Usage
**Testing the Integration**:  
* Watch the 5 minute video demo [Constant Contact Integration Suite for Salesforce Demo](#) on how to use the integration  
  
🎥 **Video Timestamps**:
* **0:00**: Storing the client id, client secret, access and refresh tokens.
* **0:00**: Create the event record in Salesforce
* **0:30**: Verify event record creation in Constant Contact.
* **1:00**: Create the event registrantion record in Salesforce.
* **1:30**: Verify event registration record creation in Constant Contact.

⌛️ **Access Token Expiration:**  
* Tokens expire after 1,440 minutes; refresh logic is included to keep the integration active. 
* Uses Salesforce’s secure Named Credentials and OAuth 2.0 for safe API interactions.  
* Contributions, issues, and feature requests are welcome! Feel free to check issues page if you would like to contribute.
