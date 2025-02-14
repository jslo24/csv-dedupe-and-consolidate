**To set this up:**

**Create your sheets structure:**

Copy headers from your original CSV to both "Raw Data" and "New Imports" sheets
Create your pivot table in "Pivot View" sheet
Ensure both sheets have an "email" column (case sensitive)


**Save and authorize the script:**

Click the save icon (💾) in the Apps Script editor
Close the Apps Script editor
Refresh your Google Sheet


**Usage:**

You'll see a new menu item "Data Tools"
Team members can:

Paste new data into "New Imports" sheet
Click Data Tools > Process New Data
The script will:

**To use this:**

Make sure both sheets have a linkedinProfileUrl column (exact spelling)
Records with LinkedIn URLs will be deduped
Records without LinkedIn URLs will always be added with a timestamp
You'll see how many records were added and how many duplicates were skipped

**This setup allows you to:**

Maintain one source of truth in "Raw Data"
Prevent duplicates
Track when contacts were added
Keep your pivot table intact
Give team members an easy way to add data

