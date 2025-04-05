# dfcasestudy-
digital forensics , ethical hacking the analysis and investigation process taking an example of Chinese phishing web site 
[README.md](https://github.com/user-attachments/files/19613555/README.md)


PERFOMING THE OSINT ON THE WEBPAGE - that means to oprate and find all the information passively (not directly connect and exchanging packets with it )

*-http://regulation-dsq.top/login*

![Pasted image 20241102153419](https://github.com/user-attachments/assets/d99b6def-13bd-4270-b37d-74f921e7cd61)


**ping** - to find the **ip address** of the web 
      - 192.151.194.100
**whois** - searches a user name directory and displays information about the user ID or nickname specified in the Name parameter




![[Pasted image 20241102153419.png]]

![[Pasted image 20241102155730.png]]

![[Pasted image 20241102160046.png]]

![[Pasted image 20241102160905.png]]

**curl** - to get the html, css, js code  of the website . 

> ''    > **file.txt** to send the output into the file 

![[Pasted image 20241102155730.png]]



-  - used for 
![[Pasted image 20241102160046.png]]![[Pasted image 20241102160905.png]]bythis we can say  the domains that are runing using the same server 


dig - **retrieving information about DNS name servers**.
![[Pasted image 20241102163334.png]]


- ==**Shodan**== (Sentient Hyper-Optimised Data Access Network) -  is a search engine designed **to map and gather information about internet-connected devices and systems**.
			this website is used for the tracking the location, openports, vulneabities, of that server 
			![[Pasted image 20241102164809.png]]


crt.sh - this site is actually gives the sss certificate for the websites soo they can have HTTP***S*** 

but the all the domains under the server are linked together.

so when we search a website we can find **ALL THE DOMAINS** 


![[Pasted image 20241102165442.png]]


![[Pasted image 20241102165924.png]]
THIS WEBPAGE DO NOT HAVE A CERTIFICATE OF HTTPS 
