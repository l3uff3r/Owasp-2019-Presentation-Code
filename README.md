Well this is my reverse engineering presentation for Owasp Latam Tour 2019 
Compile Program:
      gcc -o crackme crackme.c
      
The current c project shows as an example vulnerabilities we can find in static analysis which are:
 
 1.- Hardcoded Properties("in this case the crackme login password")
 2.- Password variable size is fixed("declares variable size as 30 and does not do any type of verification if limit is passed")
