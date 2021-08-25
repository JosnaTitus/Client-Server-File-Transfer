                                                  Multi-Connection Server Client File Transfer
 
> Brief about the program:-

              	A simple file transfer server written in Python 3, that allows the user to download files located on the server. The server can handle and serve multiple clients at the same time and send files in the same/child directories.
	
> Instructions to run the command:-

	Run the server.py file, entering the port you wish for the server to run on. It will generate an IP address.
	Now, users can run the client.py file and connect to the server by entering the IP address and port displayed on your server.
	A user can enter the name of a file on the server (in the same folder as the server.py) and download that file - the file will appear in the same directory as the client.py file, named from_server+filename.
	You can connect the server to multiple clients and also transfer multiple files.

> Commands to run the program:-

    How to run the server code:-
        1. Open Terminal in the given folder
        2. python3 server.py
        3. Enter Port Number
        4. Copy the IP address provided by server.

    How to run the client code:-
        1. Open as many Terminal you want in the given folder for the client and run the process given below.
        2. python3 client.py
        3. Enter IP address copied from the server code
        4. Enter File name.
        5. Check if the file is copied successfully in the given folder.   

> Requirements:-

    Python 3.7+
    Socket Module (standard library)
    Threading Module (standard library)
    OS Module (standard library)
