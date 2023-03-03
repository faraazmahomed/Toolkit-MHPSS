# What is this repository?

    This repository contains files that constitute the Beta Pilot, Nepal, Pode Falar and U-Matter projects, which is separated into two folders. The 'Workspace' folder includes specifications, configurations, and the base that forms the flows of the project's components. The 'AI' folder provides information about the Artificial Intelligence utilized, along with its datasets for each of them.

## All files are in JSON. What is JSON?
    JSON stands for JavaScript Object Notation and it's a lightweight format for storing and transporting data. JSON is "self-describing" and easy to understand.

## What does each file report?

**Workspace folder:**

+ **channels.json**: name of activated channels and their corresponding UUID and creation date;

+ **contacts.json**: UUID of the contact, urns, groups the contact belongs and all their contact fields filled in;

+ **flows.json**: UUID of the flow, its name and flow settings. It can be imported into another Workspace;

+ **globals.json**: global variables and their values;

+ **groups.json**: UUID of al the existing groups and its name, conditional query (only for Smart Groups) and number of users belonging to it;

+ **labels.json**: UUID of the label and its name, along with the number of occurrences;

+ **template.json**: Template Message UUID and its name, the configured language, its namespace, status and the channel in which it was activated.
	
**Artificial Intelligence folder:**

+ Contains the number of trained phrases, text of the phrases, their intentions, language, and date of creation for each AI used in the projects.  


# How to import Workspace files in Dash platform?

Once the files have been downloaded, log in to the [Dash](https://dash.weni.ai/) platform and navigate to the desired Workspace. Then, in the "Flows" tab, click on "Import" located in the right-hand corner.

Select the file you want to upload and then click on the "Import" button:

Please wait a few moments, and soon the files will have been imported!
You can confirm that everything went well in the same "Flows" tab. You may need to refresh the page by pressing F5 on your keyboard or by clicking on the "reload this page" button in your browser.
