# How to upload metadata

### Introduction
This repository contains all the metadata files on the [platform](https://modi-data.github.io/).\
[MODI](https://modiproject.eu/) parteners can upload their metadata files here.
These files will automatically be uploaded to the platform.
Other users can then search for these files and in the end use them find and use the right datasets for their research.

To upload to this repository you first need to become a **contributor**.

### Becoming a contributor
Send an email to **TEMP NAME**.\
State what organization you are from and what the name is of your Github profile.

### Uploading a file
Go to the [yml folder](https://github.com/modi-data/modi-metadata/tree/main/yml).
![image](https://github.com/modi-data/modi-metadata/assets/129458694/8e7a1d70-ce2c-4c4e-af12-ab30aa15daca)

Click on *add file*.
![image(1)](https://github.com/modi-data/modi-metadata/assets/129458694/6a8bc943-7db6-44b8-9af7-4978c6611a6f)

Add the files you want to upload.\
Click on *Propose changes*.
![Screenshot from 2024-02-20 16-35-06](https://github.com/modi-data/modi-metadata/assets/129458694/82242d10-8974-49be-a4be-7ce544e1f70a)

Click on *Create pull request*
![Screenshot from 2024-02-20 16-37-03](https://github.com/modi-data/modi-metadata/assets/129458694/8ad9bd09-7dca-4d25-880e-4a52f936ffc4)

Click on *Merge pull request*
![image](https://github.com/modi-data/modi-metadata/assets/129458694/56f22da8-9425-4b75-bb69-a7b61d7ee7cf)

You are done!

If you received an error in the last step then that probably means that you accidentally tried to change a file that you are not allowed to change. Make sure that every file you uploaded is of the form yml/*.yml (it is in the yml folder and has .yml as a file extension).
If you encounter any other problems contact the admin.

# Architecture
This repository represents the modi-metadata section of the architecture displayed below. This repository is responisble for receiving the metadata files from the upload site/authenticationserver, storing the metadata files, constructing the database file from these metadata files and sending the newly created databse file to the modi-data.github.io repository.
![Alt text](Modi-Architecture.drawio.png)
