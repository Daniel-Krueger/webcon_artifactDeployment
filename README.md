# Artifact deployment

A WEBCON BPS application to deploying artifacts.

The folder contains the application for the specified version as well as an Excel file. The Excel file has been created by exporting the report of the application. It contains all the scripts, so if you are only interested in the scripts take a look at the Excel file.  

The application packages starting with BPS version 2021.1.3.205 don't contain any data. If you are interested in the scripts you can take a look at the Excel or import it directly.
# Database scripts
Is part of the initial version of the application "Artifact deployment". It contains database scripts which are also separately stored in the Excel file.
More information about this process can be found [here](https://daniels-notes.de/posts/2021/deploying-database-scripts)


# Assembly deployment
Starting with version 2021.1.3.205 the template contains a process for deploying assemblies. The script `RemoteDeployment_fromBPS.ps1` has been used for the development of the script used by the process. The starting if clause is used during development while the remaining script can be copied to the PowerShell action. The whole script can not be copied because of the base64 string.
More information can be found (will be added): 