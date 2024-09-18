﻿# Email-To-File-Sorting
 
This is a project I made in my spare time at my internship to automate a time-consuming process where I daily had to manually download PDF attachments in my email and put them in the correct directories all around our shared Google Drive.

# How to Use
## Step 1
Create a new project on [console.cloud.google.com], click on the "APIs & Services" button in the hamburger menu. Configure your OAuth consent screen and add scopes `.../auth/userinfo.email` and `.../auth/gmail.labels`. Download your client_secrets.json and add it to the directory where you cloned the project.

## Step 2
Rename the paths in the `email_finder.py` and `file_sorter.py` to match your needs. 

## Step 3
Run main.py, log in with your Google account, and let it run! If you want, you can use a cronjob or task scheduler to automatically run the script at a certain time or when certain conditions are met.
