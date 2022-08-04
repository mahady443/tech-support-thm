<img src="img/maxresdefault.jpg" >


first scan the ip address given to you with nmap

nmap -sC -sV IPADDRESS -oA nmap

find some open port 

scan the address with gobuster with directory list 
find 2 new directory

then try to connect via smbclient with ip address with no login credentials 


find a enter.txt file //read the enter.txt


from that file we find more directory with username and password

we need to decrypt the password 

login

we find the cms version

search via searchexploit 

find the vulnerability 


try to exploit with fileupload 
then use php-reverse-shell.php file for reverse shell

change file type .php to .phar


try to connect with netcat 

and get the flag