Computer Networks : Assignment 2
---------------------------------
Socket Programming :
	Compiling code : gcc 201356204.c -lcrypto -lssl
	To run code : ./a.out

After running, it asks for the host port and then next server port. These should be vice versa while running the server and client

And then :
	To run commands through TCP protocol, select 0
	To run commads through UDP protocol, select 1
	To allow file upload type FileUploadAllow else FileUploadDeny


Commands:
	IndexGet longlist
	IndexGet shortlist {timestamp} {Example: IndexGet shortlist WedJul0909:02:262014 FriFeb0618:23:442015
	IndexGet regex .*c
	FileDownload <filename>
	FileUpload <filename>
	FileHash verify <filename>
	FileHash checkall
