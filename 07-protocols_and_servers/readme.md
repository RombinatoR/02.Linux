# Protocols and servers

## Goals  

1. HTTP/HTTPS
    - Configure a virtual host
    - Deploy a one pager 
2. SSH 
    - Configure key-based authentication
3. SMB
    - Provide network shares to specific clients
4. TELENET
    - Install and configuration
5. FTP
    - Install and configuration


## HTTP, FTP, SMTP, POP3, IMAP, SMB.

First, please follow tthese pdf :
- http://dma.vgtu.lt/KTA/KTA10_EN.pdf

## Exercises

> Connect to the virtual machine 10.12.181.X with the following credentials:  
> * ip : 10.12.181.X  
> * user : student  
> * password : student  

1.  On your kali (or other) , install ``ngnix`` to have an http server on port 8080. Replace the default page of ngnix by an html page displaying a hello world.
    > No answer required

2. What other well-known service could be used instead of nginx? 
    > Your answer : **Apache** (among others)

3. On your student machine, create a temporary http server with python, on port ``5000``. Then on your kali machine, open a browser and go to the address ``10.12.181.X:``.
    > Your command : 

4. Let's imagine that a hacker owns the domain name ``g00gle.com``, which tool would allow him to obtain an ssl certificate (https) very easily?
    > Your answer : **certbot**

5. On a linux machine, what tool could you use to have a self-signed SSL certificate on your local machine (localhost) ? 
    > Your answer : **openssl**

6. On your student machine, install the ftp service and connect from your kali machine.
    > No answer required

7. What is the default port for ftp? 
    > Your answer : **21**

8. Is the ftp protocol secured?
    > Your answer : **Not by default; however there exists FTPS**

9. On your student machine, install the telnet service and connect from your kali machine.
    > No answer required

10. What is the default port for telnet? 
    > Your answer : **23**

11. Is the telnet protocol secured?
    > Your answer : **No**
    
12. Create a share file with samba between your Kali machine and your student machine.
    > No answer required






