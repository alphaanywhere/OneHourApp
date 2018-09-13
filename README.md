# OneHourApp
Resources for building an application following the Alpha Anywhere Mobile App in an Hour tutorial.

For a tutorial for how this application was built, visit https://www.youtube.com/watch?v=wHnSIX7dJu0

## How to Download and Install this Project
1. Click the Clone or download button and select the Download Zip option to download the application.
2. Extract all files from the .zip file.
3. When extraction is complete, launch Alpha Anywhere and open the Alpha Anywhere .adb file located inside the folder where the extracted files were saved.

For detailed instructions, see [How to download a Sample App from the Alpha Anywhere GitHub Repository](https://www.alphasoftware.com/documentation/index?search=how%20to%20download%20a%20sample%20app%20from%20the%20alpha%20anywhere%20github%20repository).

## Setting up your Workspace
In order to use this component, you must create an AlphaADO Named Connection called "conn" that connects to the Access Database "onehourapp.mdb".

Alternatively, you can re-create the database in your SQL Database system of choice from the onehourapp.sql file and configure your "conn" connection string to point to the database you created.

## What's in box?
The following files are in this repository:
1. alphaOneHourApp.adb - The Workspace file.
1. onehourapp.mdb - An Access database file
1. onehourapp.sql - A sql file for re-creating the Access database in the SQL Database system of your choice
1. main_ux.a5wcmp - The UX Component that contains the application.
1. .gitignore - A file used by git that lists files and folders to "ignore". If you fork this repository to your own GitHub account, the files and folders listed in this document will not be check into git. See [How To Configure Source Control to Ignore Alpha Anywhere Files](https://documentation.alphasoftware.com/index?search=howto%20configure%20source%20control) to learn more.
