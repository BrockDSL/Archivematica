# Getting started

You'll need to install some software in order to use Archivematica. The software you install depends on your operating system.

You will also need an Archivematica account--Isaac will set this up for you when you begin work on the project.

Note: If you are using a Brock computer and run into problems installing the software, this is most likely due to insufficient permissions. If this happens, contact Isaac via Teams or Slack and let them know the error you are encountering.

## Windows

### makeCSV

Steps:

- Download this file: [makeCSV.zip](https://spotdocs.scholarsportal.info/download/attachments/186974835/makeCSV.zip?version=2&modificationDate=1556913915000&api=v2)
- Extract the file
- Double click on the makeCSV folder
- Double click `makeCSV.reg`
- When you see a window asking if you would like to allow the program to make changes to your computer, select "Yes"
- A second window will ask if you are sure you would like to continue; select "Yes" again
- If the installation was successful, a third window will appear, saying that the keys to the program have been successfully added to the registry; select "OK"

Using makeCSV:
- Navigate to the folder where you would like to add metadata
- Right click any file in this folder and select "makeCSV" from the list of menu options
- This will generate a `metadata` folder with a spreadsheet where you will add metadata

### Exactly

Steps:
- Click on [this link](https://www.weareavp.com/products/exactly/) and download Exactly for Windows
- Unzip the file
- Click on the "dist" folder
- Click on the "bundles" folder
- Double click the .exe file to open the program (you may also save the .exe file in a location that provides quicker access, such as the Desktop)

### 7-Zip

By default, Archivematica compresses AIPs as 7z files. The 7-Zip utility allows you to extract the files. 

Steps:
- Click on [this link](https://www.7-zip.org/)
- Download the 32- or 64-bit version depending on your installation of Windows
- Double click the .exe file and install
- Consult the Archivematica workflow documentation for instructions on opening 7z-type AIPs

## MacOS

### makeCSV

To install makeCSV on a Mac, you'll need to run a script.

Note: This script only works for files in a top-level directory. Sub-directories will not be included.

Steps:
- Download the file [makecsv.sh](https://spotdocs.scholarsportal.info/download/attachments/186974835/makeCSV.sh?version=1&modificationDate=1532629069000&api=v2)
- Copy and paste the script file into the folder you want to inventory
- In Terminal (or your preferred command line program), use the `cd` command to navigate to the directory. For example, if you are looking to inventory an "objects" folder on your Desktop, which is located at /Users/yourusername/Desktop/objects, type `cd /Users/yourusername/Desktop/objects`
- After using the `cd` command, type `bash makecsv.sh` and hit enter
- A metadata folder will appear in a new directory at the same level as the folder you inventoried
- Delete the makecsv.sh file from the original folder
- Add metadata to the CSV
- Add metadata directory to your transfer as part of the Permafrost transfer workflow

### Exactly

Steps:
- Click on [this link](https://www.weareavp.com/products/exactly/) and download Exactly for Mac
- Unzip the file
- Double click the application file icon to open the program (you may also drag the file to a location that provides quicker access, such as the Dock)

### Unarchiver

Steps:
- Click on [this link](https://theunarchiver.com/) and download the Unarchiver
- Install the program
- Consult the Archivematica workflow for instructions on opening 7z-type AIPs
