# PowerExtensions
Small scale extensions for D365 and the Power Platform

# Exchange Contacts Import Page

**Creator Kit is required for importing the solution!**

Custom Page to import Exchange contacts from the current user to dataverse. The page uses the Outlook365 connector to retrieve contact folders and contacts and a dataverse connection to import the selected contacts.
Company names may be mapped to dataverse accounts, with the parent account of the imported contact being set to the chosen account. Other imported fields are firstname, lastname, email, job title, business phone, mobile phone, address 1 and birthday.

A basic duplicate check is included, checking for any contacts in dataverse accessible by the logged-in user with the same primary mail as the exchange contact.

*Managed and unmanaged solution available under Releases*

# Import Feedback Flow

Power Automate flow to inform users when an import they started is finished.
Once an import finishes, the user who created the import will receive an In-App Notification (needs to be enabled in your model driven app settings) informing them that it is finished, if any errors occured during import and link them to the import file with instructions on how to download the errors and prepare for reimport.

*Managed and unmanaged solution available under Releases*
