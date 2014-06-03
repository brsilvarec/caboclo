CABOCLO
---------

Caboclo (Client API for Backup on Cloud), which provides a REST/Full API for supporting backup/restore operations considering cloud infrastructures. The tool's API allows programs written in different languages to create backups in several cloud providers (e.g., Amazon S3). By using Caboclo, developers can use different cloud storage services by a unified API simplifying the development task.

![Alt text](https://dl.dropboxusercontent.com/u/887480/CabocloStructure.png "Figure 1: Caboclo Overview")

Figure 1 presents the Caboclo high level structure. In this picture, the user program performs REST calls to Caboclo describing the selected operation (e.g., data backup or restore) and the desired cloud environment (e.g., Amazon S3) and the user data is transferred from/to the cloud service. The supported cloud infrastructures are: Amazon S3, OpenStack, Dropbox, Microsoft OneDrive, Google Drive.
