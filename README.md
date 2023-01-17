SalesForce Data Extractor (for Firefox):
===

### # What it is:
It is a Firefox Add-On/Extension.<br />
It has been designed with in mind any _Enterprise Spectrum Technician (6th level)_; it provides an easy tool (script) that *aim to help* to quickly collect the most useful information in order to build the _Cut-Sheet_ document needed for the job.

### # Why it's useful:
It is useful because it can quickly help to extracts the most essential data from a __Salesforce ENG# page__ and then it will present these information into a popup window as a temporary webpage _(that will automatically close after about 10 minutes)_.

### # How it works:
It is mainly a script in JavaScript language that retrives/extracts specific fields from a __Salesforce ENG# webpage__ and will format these information in a new popup webpage created ad-hoc for this specific needs.<br />
The script is launched in background as the user will click on the extension/add-on icon.<br />
The script will **automatically collect/extract** specific **information** from the opened ENG# page and will **organize them in a more clean and concise way** for the end-user, **creating a new webpage as a popup window**.<br /><br />
This popup page will contain some easy useful additional JavaScript that can help the user to interact with it...<br />
_Example: one-click on a field-value will copy its textual content to the user-clipboard, so to make it easier to copy specific information elsewhere as needed._

### # Get-Started:
To get started and use this tool, the best feasible way is to visit the addons pages of Firefox and Add/Install this addon directly from there.<br />
Here is the link to be redirected to the Add-On:<br />
[https://addons.mozilla.org/en-US/firefox/addon/salesforce-data-extractor/](https://addons.mozilla.org/en-US/firefox/addon/salesforce-data-extractor/)<br />
Otherwise, you can _clone this project_ and _build it locally_ so you can install it yourself on your browser following the suggested manual installation instructions [here below](https://github.com/steo82rm/SalesForce-Data-Extractor-x-Firefox-/edit/main/README.md#manual-installation-only-localno-auto-updateonly-for-linux-os).<br />

### # Manual installation:
Please, before to proceed, consider the following:
- keep this package version and it is a local installation;
- most probably there will be no auto-update feature;
- the following information provided are valid and good ***ONLY for any LINUX OS*** ...
- the script _make_ can be used to facilitate the build of the package.

To proceed with the manual installation follow these instructions/commands:<br />
`mkdir SalesForce_DataExtractor_xFirefox`<br />
`cd SalesForce_DataExtractor_xFirefox`<br />
`git clone https://github.com/steo82rm/SalesForce-Data-Extractor-x-Firefox`<br />
`chmod 754 ./make`<br />
`./make`<br />

- inside the folder `./builds` there will be the so built extension named: _`SalesForce_DataExtractor_xFirefox_YYYY-MM-DD_hh-mm-ss`_
- to install it: double click-it  ( or copy it into the Firefox profile directory: _`/home/<username>/.mozilla/firefox/<userprofile>/extensions/`_ )


### # Mantainer and getting help:
I am the only mantainer of this simple project at the moment... and this is a work-in-progress still, but while adding a few easy functionality: the goal, the scope, and the main flow of this Add-On/script will remain exactly the same and pretty much unchanged.<br />
If any help is needed or for any question please contact me here on github.

<br />

### ⚠ Important notes: ⚠
1. In order to allow this extension/script to efficiently run, the user will _need to allow popups windows from the domain: "**[salesforce.com](https://salesforce.com)**"_
    - _a quick official guide on how to achieve this configuration for the Mozilla Firefox browser can be reached here:_
      _[https://support.mozilla.org/en-US/kb/pop-blocker-settings-exceptions-troubleshooting](https://support.mozilla.org/en-US/kb/pop-blocker-settings-exceptions-troubleshooting)_
2. The script is designed to be effective and to run _only on the domain: "**[salesforce.com](https://salesforce.com)**"_


 
---
### About Me:
<picture style="float: left;">
 <source media="(prefers-color-scheme: dark)" srcset="https://avatars.githubusercontent.com/u/114833388?s=400&u=ae7813769b528e419e049624801e7eb8017ba7a8&v=4">
 <source media="(prefers-color-scheme: light)" srcset="https://avatars.githubusercontent.com/u/114833388?s=400&u=ae7813769b528e419e049624801e7eb8017ba7a8&v=4">
 <img alt="My Avatar" src="https://avatars.githubusercontent.com/u/114833388?s=400&u=ae7813769b528e419e049624801e7eb8017ba7a8&v=4">
</picture>

> [DOH!](https://github.com/steo82rm/SalesForce-Data-Extractor-x-Firefox-/edit/main/README.md#salesforce-data-extractor-for-firefox)

— Homer J. Simpson


I am an enthusiast amatorial programmer with, at the moment, little time for it.<br />
I hope to share some of my knowledge to this community and to provide useful contributions, nevertheless to learn new things.
<!-- TO DO: add more details about me later -->
Thank you for using and contributing to this little project of mine; any contribution may be precious and sincerely welcome!

