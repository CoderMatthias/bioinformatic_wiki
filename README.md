# UNC bioinformatics wiki
Scripts to assist with the UNC bioinformatic services.

## **Scripts**

#### set_up_project.sh
The purpose of this script is to set up an organized folder structure for big data projects.
###### Description:
As projects progress and data accumulates, an orderly system for file storage will allow easy identification raw vs processed data files, final outputs, logs, and the scripts used to process this data.

###### Usage:
Move the set_up_project.sh script to the folder where you want to set up your project.  (this could be in your scratch folder, luster, or your proj [if you have one]) Then run the following command: 
```
bash set_up_project.sh
```

Script will then request the project name and create a folder of said name that will contain the following folders and files:
```
  00_logs
  01_ref          
  02_raw_input
  03_processed_input
  04_final_output
  05_scripts
  06_test
  READ_ME.txt
```
The READ_ME.txt is meant to be a data lab notebook which is updated as the project progresses.
