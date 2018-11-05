# MJML__WK_Template
MJML Email Templates for Wolters Kluwer

# MJML__WK_Include
MJML Email Include Files for Wolters Kluwer

# Additional Info:

BlueLink fix:
1.	For URL we wrap in `<span class=”white-link”>http://prawo.cc</span>` or add class and style to <a>
2.	For e-mail address in body that should be __inactive__ we paste `&#8203;` between domain-name and .tld, f.e. prawo`&#8203;`.cc
3.	For e-mail address in body that should be __active__ we wrap it in `<a href="mailto:kontakt@prawo.cc" target="_blank" class="white-link" style="color:#ffffff;">kontakt@prawo.cc</a>`. Class color and style color should match. Text address and mailto address should match. It's best to omit creation of _mailto_ on non-email text (f.e. "Contact us") as it is sometimes blocked for consumer security by email clients.
  
Folder Structure:

- Main Folder
  - WK Template (subfolder)
  - WK Include (subfolder)
  - User Mails (subfolder)
  - Another Mails (subfolder)
  
Do not create sub-subfolders unless just for archivisation needs as it will brake relative links to WK Includes.

