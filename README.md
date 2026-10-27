# Flask FTP Server (Using Python / HTML)

These scripts are used for building an FTP style html server on your own hardware.  

`download-server.py` -> Flask python server for serving dynamic .tar downloads  
`fixperms.sh` -> Easy bash permission-solving script for bad imports  
`hash.py` -> Script that generates checksums for each folder  
`html_gen.py` -> The script used to generate HTML index files for each folder  

This still needs hosted through a conventional web service like NGINX or APACHE    

*note: don't use this outside of a trusted environment, flask is not secure.*
