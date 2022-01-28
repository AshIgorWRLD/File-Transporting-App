ABOUT: console app for transporting files between users, has 2 working states: server - receiving files, client - sending files; server saves received files in "receivedFiles" directory of project directory

SERVER ARGUMENTS: required argument - "s", port number which will be used by server, optional argument - "clean" (if you need to clean directory of receiving files)

CLIENT ARGUMENTS: required argument - "c", IP address of server that will receive sending files, port number which will be used by client, path to sending file (if file in "filesToSend" directory of project directory you need to write "filesToSend\your_file.your_file_extension", else you need to write full path to your file)