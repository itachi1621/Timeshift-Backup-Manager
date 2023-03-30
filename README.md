# Timeshift_Backup_Manager

This script is a simple backup manager for Timeshift, 
a popular backup tool for Linux systems. 
With this script, you can easily manage your Timeshift backups without having to know the commands.


## Features
- Easily create backups of your system.
- Clean up old backups to free up disk space.
- Create backups with Daily, Monthly, Weekly Tags.
- Easy access to timeshift features without knowing the commands.

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
or

``` 

sudo sh Timeshift-Backup-Manager.sh 

```

## Usage 


![Timeshift backup manager menu](https://user-images.githubusercontent.com/62318474/228902206-57caadaf-0c49-4c31-9aad-552b79049acc.png)

## Timeshift repos
### Original Timeshift repo
- https://github.com/teejee2008/timeshift
### Linux Mint Repo
- https://github.com/linuxmint/timeshift


## License
This script is licensed under the MIT License.
