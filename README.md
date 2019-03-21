# MJML Templates & Includes

All that is needed to create unique e-mail using MJML

## MJML Version

Wolters Kluwer files are created and maintained in MJML3 (Templates v2.3)
Sanofi files are created and maintained in MJML4 (Templates v0.1)

## Folder Structure

- Main Folder
  - Template (subfolder containing templates)
  - Include (subfolder containing common modules)
  - Mail Folder 1 (subfolder with custom e-mails using includes)
  - Mail Folder 2 (subfolder with custom e-mails using includes)

Do not create sub-subfolders unless just for archiving needs as it will brake relative links to Include files.

## Additional Info

BlueLink fix:

1. For URL we wrap in `<span class="white-link">https://mateuszdabrowski.pl</span>` or add class and style to <a>
2. For e-mail address in body that should be __inactive__ we paste `&#8203;` between domain-name and .tld, f.e. mateuszdabrowski`&#8203;`.pl
3. For e-mail address in body that should be __active__ we wrap it in `<a href="mailto:github-mjml-readme@mateuszdabrowski.pl" target="_blank" class="white-link" style="color:#ffffff;">github-mjml-readme@mateuszdabrowski.pl</a>`. Class color and style color should match. Text address and mailto address should match. It's best to omit creation of _mailto_ on non-email text (f.e. "Contact us") as it is sometimes blocked for consumer security by email clients.
