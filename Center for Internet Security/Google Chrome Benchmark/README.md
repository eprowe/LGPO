Policies are from the Center for Internet Security's Benchmark for Google Chrome and listed in the order they appear in the Group Policy Editor.

Download Google Chrome and Google Update Group Policy templates from here: https://www.chromium.org/administrators/policy-templates.

Download LGPO from here: https://www.microsoft.com/en-us/download/details.aspx?id=55319

Specific policy notes:

**Google\Google Chrome\Password manager\Enable saving passwords to the password manager - Disabled**

CIS recommends this polisy be configured to meet an organizations needs.  It is disabled in this file.

**Google\Google Chrome\Remote access\Configure the required domain names for remote access clients - Enabled**

This policy requires a domain be entered.  It is intentionally left blank.

**Google\Google Chrome\Enable Chrome Cleanup on Windows - Disabled**

CIS recommends this policy be configured to meet an organizations needs.  It is disabled in this file.

**Google\Google Update\Applications\Google Chrome\Update policy override - Enabled: Always allow updates**

CIS recommends either 'Enabled: Always allow updates' or 'Enabled: Automatic silen updates only'.  This file uses 'Enabled: Always allow updates'
