# LogosReadingPlanEditor
I created this tool for convenience that can update pages when the day is out of sync as some pages of the resources contains more than 1 page. So just sharing this out to anyone that needs it. 

For example I want to update 3 / 4 resources in a reading plan without recreating everything. 

## MacOS Path for Reading Plan database : 
/Users/YOURUSERNAME/Library/Application Support/Logos4/Documents/RANDOM_AlphaNum/Documents/ReadingPlan/ReadingPlan.db

## Steps : 
1. Download the index.html to your local folder.
2. Double click the index.html to open with any browser.
3. Install Beekeeper Studio (I'm not promoting just stating what I used in reality) or any preferred database reader.
4. Copy the ReadingPlan.db to other folder as backup. 
5. Open the ReadingPlan.db > ReadingPlanDocuments table and copy the JSON data from column of Sessions.
6. Paste the JSON data into the text area at the left side.
7. Click Load Data.
8. For example, to update :
   2026-02-03 Resource 1  - 173 to 176, Resource 2 - 145 to 148, Resource 3 - 146 to 148.
   Change the page number by typing the desire page.
9. Click Update.
10. Click Copy Compressed JSON.
11. Paste it into the Sessions column where you copied in the first place at Step 5.    
12. Click Apply button at the bottom right to Update the data.
13. Open the Reading Plan in Logos, it should show tupdated pages. 

# Note : Always keep a backup no matter what so that you can always revert. Best practice is to duplicate the original Reading Plan first, then backup the db as well so that you can always fall back to the untouched copy. 
