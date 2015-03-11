#Computer Networks : Assignment 2

##Socket Programming :
	1. Compiling code : gcc 201356204.c -lcrypto -lssl
	2. To run code : ./a.out

* After running, it asks for the host port and then next server port. These should be vice versa while running the server and client

* And then :
	1. To run commands through TCP protocol, select 0
	2. To run commads through UDP protocol, select 1
	3. To allow file upload type FileUploadAllow else FileUploadDeny


##Commands:
	1. IndexGet longlist
	2. IndexGet shortlist {timestamp} {Example: IndexGet shortlist WedJul0909:02:262014 FriFeb0618:23:442015
	3. IndexGet regex .*c
	4. FileDownload <filename>
	5. FileUpload <filename>
	6. FileHash verify <filename>
	7. FileHash checkall
