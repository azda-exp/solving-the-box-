# solving-the-box-
I will tell you step by step how to solvi the dancing box in HTB 
#first lets perform a normal nmap scan :
sudo nmap -sV -pn IP
#well a SMB port cut my attention so lets connect it useing SMB client :
smbclient -L IP
#i see some shares some acailable some not but the workshare is so lets connect to that :
smbclient IP/workshare
ls
#we can see flag.txt but dont make the mistake of reading on the box networke first download it and submit the flag 
