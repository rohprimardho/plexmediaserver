# plexmediaserver
This is an ansible playbook to setup Plex media server with Sickbeard ans Sabnzbd. It also uses ansible-vault to encrypt the file that contains sensitive information. 

I include the decrypted file so then it can be used also by other people. It is empty though. ;) 

Have fun! 

Note:
* With these roles, it is possible to define different (Linux) user that will run sabnzbd and sickbeard. If the goal is to make both apps work, using only one user is recommended. The problem is at one point, sabnzbd user will need to access sickbeard dir. It won't work with different users. 
