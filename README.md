# Deb Installer
An Automatic Debian file installer. The `scanner` files is the only file need and it doesnt need to be ran with sudo,becuase it aks for permssion once it has found a file. What this does is scan a download folder in this case `/user/$user/downloads` for any file with the extention `.deb` and runs a set of commands for it. It will find the following.
  - Name
  - Depends
  - Author
  - Size
  - Version
  - Description
  - Package Name
  
## Process
One of the first things it does is check to see if the package has all ready been installed. if so it checks the version of the installed version and the new downloaded version. If the version numbers are diffenre it will automatiiclly update the application and just needs your passcode. If the application is already installed and the downloaded is the same version all reasdy installed it will delete the file and move it to the trashcan. If the package snt installed the system will gather info about it and give it to you asking for the install.
