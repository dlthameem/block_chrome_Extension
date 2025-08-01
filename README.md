# block_chrome_Extension
The code restricts all chrome extensions and allows only the mentioned chrome extensions,.

# Chrome Extension Block

Use the following process in jamf pro to add the XML PLIST file to control the chrome extensions.

Go to Computers -> Configuration Profiles -> Click New.

In General tab: Give some name e.g., like “Block Chrome Extensions"

Go to the Application & Custom Settings payload, then 

Click Upload -> Add

Preference Domain :  com.google.Chrome

Paste the plist in the Property List Box.

Give the Scope and Save. 
