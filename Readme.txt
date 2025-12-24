4. Pushing scraped files to GitHub

After generating the CSV files, follow these steps:

Step 1: Check Git status
code : git status


You should see scraped_data/ files as untracked.

Step 2: Add the files
code : git add "scraped_data/*"


Make sure to include all files inside the folder.

Step 3: Commit the changes
code : git commit -m "Add newly scraped CSV files"

Step 4: Push to GitHub
code : git push origin main


Replace main with your branch name if it’s different.