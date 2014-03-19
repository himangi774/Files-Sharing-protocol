----------------------------------------------    README      ---------------------------------------------------------
Computer Networks Assignment 1
Application Level file sharing protocol with support for upload/download and indexed searching
------------------------------------------------------------------------------------------------------
Himangi Saraogi (201201074)

------------------------------------------------------------------------------------------------------
Compile using : cc -o ftp filetransferprotocol.c -lssl -lcrypto
---------------------------------------------------------------------
Run using
./ftp <client portno> <ip of server> <server portno> <protocol>

Commands Supported : 

IndexGet
ShortList

   
IndexGet
ShortList 
starting-time-stamp
ending-time-stamp   
IndexGet
RegEx
"*mp3"  


FileHash
Verify
Name-of-file

FileHash
CheckAll

FileDownload
Name-of-file

FileUpload
Name-of-file

-------------------------------------------------------------------------------------------------------


