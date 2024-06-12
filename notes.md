# dairy-notes

### Environment variable [link](https://phoenixnap.com/kb/set-environment-variable-mac)
### npm package [link](https://www.codementor.io/@dhananjaykumar/build-and-publish-an-npm-typescript-package-1jklrmbf2g)

# linux command  

**_Terminal_** : provides UI for interacting with the computer system  

***command line***:  means of interacting with the computer system by typing textual commands instead of using a graphical interface.  

***Shell***: interprets the commands entered by the user and executes them. mac use **zsh**.  

node   
where node  
/Users/a/.nvm/versions/node/v20.14.0/bin/node  
open /Users/a/.nvm/versions/node  
/usr/local/bin/node  

environment variable  
echo $PATH: its check after :   

/ root -> Users -> a (username)(~)  

**ls**:  list all the files and directories.  
     ls -a for hidden files    
     ls -l give more info  
     ls -la  join both cmd  
     ls -R show all files in sub directories  
**cd**: change the directories  
     cd /, cd~, cd absolute path   
**mkdir**: making the directories  
     mkdir -p: make nested directories  
     
**clear**: to clear terminal  

**cat > abc.txt**: to add text  
     cat abc.txt: to open file   
     cat abc.txt bca.txt > xyz.txt : to add text of both file in third file  

**echo**  $PATH hello >  abc.txt  : add text to file  

**man**: give manual use :q to quit  
 
**touch**:  create file & updates the access and modification times   

**cp**: copy file  
     cp -R copy dir and sub dir  

**mv**: move file and dir   
     use for rename  

**rm**: remove files  
	 rm -R remove dir  

**sudo**: provide admin privilege can be use to change password of another user  

**df**: give us disk space usage   
     use -m  -g  -h for mb gb human readable  
**du**: disk usage files in cur dir  
	use -h -m  

**head**: show 10 line from top  
	  head -n  x  show  x lines  

**tail**: show 10 line from bottom  
	  tail -n  x  show  x lines  
	  
**diff**: check difference in two files  

**find**: find file and dir  
     find .  # find all the files and dir in cur dir  
	 find . -type f  
	 find . -type d  
	 find . -type f -name "\*.txt"  
	 find . -type f -iname "\*.txt"  // not case sensitive  
	 find . -type f -mmin -20 // files modified less than 20 min ago  
	 find . -type f -mmin +20  // files modified more than 20 min ago  
	 find . -type f -mtime -20 // files modified more than 20 day ago   
	 find . -type f -mmin +20 -maxdepth 1 // only show file in cur dir  
	 find . -type f -size +1k // M for mb G for gb  
     find . -perm 777 // file with 777 perm  

// ls -l abc.txt to check perm  

4 - read  
2 - write   
1 - exec  

**chmod**: use to modify the file perm  
	  chmod u=rwx,g=rwx,o=rwx abc.txt  
	  chmod 777 abc.txt   
	  
**chown**: change owner of file  // use sudo for root  
    sudo chown root abc.txt  

**grep**: search in file  
	 grep "text" abc.txt   
	 grep -w "text" abc.txt // search whole word  
	 grep -i "text" abc.txt  // not case sensitive   
	 grep -n "text" abc.txt // give line number as well  
	 grep -win "text" ./\*.txt // check in current directory  
	 grep -p "regex" abc.txt // [regex]([https://www.geeksforgeeks.org/regular-expression-grep/]))  


**uname** : give os name  
	 uname -a: os & kernel  

**uptime**: show how long system has been running   


**history**: show cmd history   
	  history | grep "cmd-name" // history of cmd  

