# ImageServer

The circumstance is, the files is supposed to be on a server where you got the images, you intend to access the images through the webpage provided by the server.
First start the nodejs server.

    
     nodejs server.js <port>

Then start another server to provide the webpage. Here for simplicity I use python SimpleHTTPServer.

     python -m SimpleHTTPServer <port>

Don't forget to specify the nodejs server address and the image folder.
