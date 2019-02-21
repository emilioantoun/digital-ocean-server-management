# Linux Commands

## Switch Users [su]

`su - rebarcity` To go from a certain user to the "rebarcity" user

## Copy [cp]

`cp [Source] [Destination]` To Copy from "Source" path to "Destination" Path

## Change Directory [cd]

`cd [Path]` To change working directory to specified "Path"

# Apache

## Restart Apache Server

`sudo service apache2 restart` to restart apache server

## Files and Folders that need root permission

  1. `sudo -i` to change to root from rebarcity user
  2. Access is granted to root

## Check error.log
  1- Change to root using `sudo -i`
  2- Copy the "error.log" file from the protected directory to the root directory `cp /var/log/apache2/error.log /`
  3- Use Filezilla to download and view error.log located in the root directory

  In case St
     
  
