# Multimedia-Forensicator
A Forensic tool for verifying the integrity of multimedia files

REQUIREMENTS
Local Server. You can download XAMPP <a href="https://www.apachefriends.org/index.html" target="_blank" >Here</a>

The target machine requires at least 
i.	2GB RAM,
ii.	2.0GHz of processor speed,
iv.	160 GB of Hard Disk Drive space


INSTALLATION PROCESS

STEP 1:
Start by installing XAMPP version 3.2.0 or a later version on the target system with all the default configuration settings. 

STEP 2:

A.	Copy and paste the folder “multimedia” to this location in the local disk drive: C:\xampp\htdocs

B.	Open the “my.ini” from C:\xampp\mysql\bin\my.ini and modify the packet size of file upload. 
max_allowed_packet = 4000M. 

Note: that this line appears twice in the document.

C.	Open the “php.ini” settings from C:\xampp\php\php.ini and modify the following values:  
  i.	memory_limit = 4000M
  ii.	upload_max_filesize = 4000M
  iii.	post_max_size = 4000M
Changing the default values to these specified values will allow room for the system to upload files with a maximum size of 40MB. 
These could be increased to allow larger file sizes.

STEP 3:
Create a new database with the name: “multimedia_forensic” and import the “multimedia_forensic.sql” file provided in the zip.


EXECUTE THE SYSTEM

Ensure that the XAMPP application is running. Open a web browser, and go to: http://localhost/multimedia


