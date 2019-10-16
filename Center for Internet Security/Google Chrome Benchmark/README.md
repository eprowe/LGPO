Policies are from the Center for Internet Security's Benchmark for Google Chrome and listed in the order they appear in the Group Policy Editor.

File was generated using template version 77.0.3865.120.  Some of the paths may not mirror those in the original CIS Benchmark.

For example, "Configure remote access options" has been moved to "Remote access"

Download Google Chrome and Google Update Group Policy templates from here: https://www.chromium.org/administrators/policy-templates.

Download LGPO from here: https://www.microsoft.com/en-us/download/details.aspx?id=55319

Specific policy notes:

Google\Google Chrome\Deprecated policies\Enable HTTP/0.9 support on non-default ports
    This policy is deprecated.  Including it anyway.
Google\Google Chrome\Password manager\Enable saving passwords to the password manager
    CIS recommends this policy be configured to meet an organizations needs.  For this LGPO file we'll keep it enabled, the default value.
Google\Google Chrome\Enable Chrome Cleanup on Windows
    CIS recommends this policy be configured to meet an organizations needs.  For this LGPO file we'll keep it enabled, the default value.
Google\Google Update\Applications\Google Chrome\Update policy override
    Two settings are recommended "Enabled - Always allow updates (recommended)" and "Enabled - Automatic silent updates only".  This file configured for the former.
Google\Google Chrome\Remote access\Configure the required domain names for remote access clients
    CIS recommends this to be enabled and a domain entered.  Each domain is unique so please adjust these settings accordingly.
    These setting need to be duplicated for each domain