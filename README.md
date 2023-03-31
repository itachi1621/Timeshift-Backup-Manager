# Timeshift Backup Manager

This script is a simple CLI (Command Line Interface) backup manager for the Linux backup tool Timeshift,  
With this script, you can easily manage your Timeshift backups via the CLI
without having to know the commands.


## Features
- Easily create backups of your system.
- Clean up old backups to free up disk space.
- Create backups with Daily, Monthly, Weekly Tags.
- Easy access to timeshift features on the CLI (Command Line Interface) without knowing the commands for timeshift.

## Requirements
- Timeshift installed and configured on your system
- Bash (version 4.0 or later)
- rsync (version 3.1.2 or later)

## Installation

1. Clone the repository: 
``` 

git clone https://github.com/itachi1621/Timeshift-Backup-Manager.git 

```
2. Move into the cloned directory with 

``` 

cd Timeshift-Backup-Manager 

```
3. Make the script executable with

``` 

chmod +x Timeshift-Backup-Manager 

```
4. Execute the script using

 **Script needs to be run as root in order to access timeshift features**

``` 

sudo ./Timeshift-Backup-Manager.sh 

```


## Screenshots

**Main Menu**

![Timeshift backup manager menu](https://user-images.githubusercontent.com/62318474/228902206-57caadaf-0c49-4c31-9aad-552b79049acc.png)

**Backup Creation Menu**

![Backup Creation Menu](https://user-images.githubusercontent.com/62318474/229012919-745848b2-6018-42ea-8f38-d40a94518da4.png)

**Backup Listing**

![Backup Listing](https://user-images.githubusercontent.com/62318474/229013480-2cbced32-e788-41ab-b429-a2ba6eebf202.png)


**Backup Deletion Menu**


![Deletion Menu](https://user-images.githubusercontent.com/62318474/229013075-1a4bec41-d0f2-4b28-b59d-1baa58f4ff69.png)

**Backup Restoration**


![Backup Restoration](https://user-images.githubusercontent.com/62318474/229013884-26e33ed9-ac99-4af7-9c56-50ae04c049e5.png)

## Tested On

- Ubuntu Server 22.04 LTS
- Ubuntu 22.04
- Ubuntu 20.04 Server LTS

## Timeshift repos
### Original Timeshift repo (Archived)
- https://github.com/teejee2008/timeshift
### Linux Mint Timeshift Repo (Current)
- https://github.com/linuxmint/timeshift


## License
This script is licensed under the MIT License.
