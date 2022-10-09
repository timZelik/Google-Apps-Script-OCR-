Author: Tim Zelikovsky
Date: 07/01/2022

# GoogleScriptsOCR
Turn a Folder with Image Files(PNG) to Google Docs Text Files

#### 1. Copy and Paste the code from the file "GoogleScriptsOCR.js" into Google Apps Scripts.

#### 2. In order to convert the files, you must create a folder with png images in your Google Drive. 
- Google Docs works with Tesseract in order to seamlessly convert images into text which is placed into a Google Doc

#### 3. Locate your folder in Google Drive and open it up.

#### 4. Copy the Folder ID and place it, in quotes, in the first two lines
- For Folder ID, go to the folder in which you have the files saved in Google Drive. Look at URL, and at the end of the URL, there should be a long combination of numbers and letters follower(ex. https://drive.google.com/drive/u/2/folders/1AIcg-ZqrvsKvSmYDHW1r9u17RCKJ2k965, what comes after /folders is the ID). Copy that ID into the given areas as a String(with quotes). Files must be in a folder.
- After "DriveApp.getFolderById()" for the variables labeled "files" and "rootFolder"

#### 5. Run the program and give it time. Once the execution completes, the files should be added to a folder labeled "Text Files"
- If you want to change the label of the folder with the text files, change the description for the variable "newFolder".
