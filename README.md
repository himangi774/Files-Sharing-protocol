----------------------------------------------    README      ---------------------------------------------------------
Compute Networks Assignment 1
	Application Level file sharing protocol with support for upload/download and indexed searching
------------------------------------------------------------------------------------------------------
Vanshika Srivastava (201201065)
Himangi Saraogi (201201074)

------------------------------------------------------------------------------------------------------
Compile using : cc -o ftp filetransferprotocol.c -lssl -lcrypto

Run using
./ftp <client portno> <ip of server> <server portno> <protocol>

Commands Supported : 

IndexGet<space>ShortList
IndexGet<space>ShortList<space>starting-time-stamp<space>ending-time-stamp
IndexGet<space>RegEx<space>"*mp3"
FileHash<space>Verify<space>Name-of-file
FileHash<space>CheckAll
FileDownload<space>Name-of-file
FileUpload<space>Name-of-file


-------------------------------------------------------------------------------------------------------


