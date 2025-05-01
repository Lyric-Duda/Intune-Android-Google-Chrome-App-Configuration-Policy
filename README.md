# Google Chrome App Configuration Policy Information

* This is my Google Chrome App Configuration Policy for Fully Managed Company Owned Devices

# JSON Configuration Information

## Google Chrome Custom Template

* I took the template that you can download from intune when you make a "App Configuration Policy" for "Google Chrome" and structured it to be "3 Space Tab"

## Google Chrome JSON Structure

This JSON file is structured to

* Enable Browser Sign In Settings
* Add Company Bookmarks to Google Chrome
* Disable Incognito Mode
* Set the homepage to the company SharePoint homepage

## Adding the Google Chrome App Configuration Policy

To create the Google Chrome App Configuration Policy
1. Navagate to Apps - Android - Configuration
2. Create a "Managed Device" policy
    * Basic
        1. Name
            * Enter the Desiered Name
        2. Platform
            * Android Enterprise
        3. Profile Type
            * Select
                + All Profile Types
                + Fully Managed, Dedicated, and Corporate-Owned Work Profile Only
                + Personally-Owned Work Profile Only
        4. Targeted App
            * Google Chrome
    * Settings
        1. Configuration Settings
            * Enter JSON data
                + Enter the JSON Data from JSON Configurations or JSON Template
    * Assignment
        1. Add desiered Users, Devices, or Groups
    * Review + create
        * Review then click create

# Demo Images

## Google Chrome Intune App Configuration Policy Settings

![Google Chrome Intune Settings](https://ldgithubstorageaccount.blob.core.windows.net/githubimages/Google%20Chrome%20App%20Configuration%20Policy%20Information/Google%20Chrome%20App%20Configuration%20Full%20Size.png)

* In addition. This policy "Auto Grants" Location permissions for Google Chrome

# Referenced Links

* [Configure Google Chrome for Android devices using Intune](https://learn.microsoft.com/en-us/mem/intune/apps/apps-configure-chrome-android)