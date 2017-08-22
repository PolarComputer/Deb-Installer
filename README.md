# Deb Installer
An Automatic Debian file installer. The `scanner` files is the only file need and it doesnt need to be ran with sudo,becuase it aks for permssion once it has found a file. What this does is scan a download folder in this case `/user/$user/downloads` for any file with the extention `.deb` and runs a set of commands for it. It will find the following.
  - Name
  - Depends
  - Author
  - Size
  - Version
  - 
