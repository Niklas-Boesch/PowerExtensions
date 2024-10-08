# PowerExtensions
Small scale extensions for D365 and the Power Platform

# Exchange Contacts Import Page

**Creator Kit is required for importing the solution!**

Custom Page to import Exchange contacts from the current user to dataverse. The page uses the Outlook365 connector to retrieve contact folders and contacts and a dataverse connection to import the selected contacts.
Company names may be mapped to dataverse accounts, with the parent account of the imported contact being set to the chosen account. Other imported fields are firstname, lastname, email, job title, business phone, mobile phone, address 1 and birthday.

A basic duplicate check is included, checking for any contacts in dataverse accessible by the logged-in user with the same primary mail as the exchange contact.

*Managed and unmanaged solution available under Releases*
