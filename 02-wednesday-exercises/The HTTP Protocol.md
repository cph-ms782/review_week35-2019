## The HTTP Protocol

[Back to readme](../README.md)  

**Statuscodes:**  
1)  
index.html: 304  

2)  
index.html: 304  
Image: 200  
CSS: 200  

3)  
redirect: 302  
r.html: 200

3a)    

4a)  
500

4b)  
404


### Exercises:
1) [Link til folder](ex1/src/main/webapp/)  
Der er request or response headers  
**Request:** Der vises metode, sti og protokol version  
Derefter en masse felter med dertilhørende værdier  
**Response:** Der vises protokol version, status kode og status text  
Derefter en masse felter med dertilhørende værdier  

2)  
Keep-alive reducerer antallet af forbindelser når der hentes ressourcer ind (som billeder og css filer)  

3)  
Upgrade-Insecure-Requests: 1  
Sec-Fetch-Site: none 

3a)  
http://studypoint.info sender videre til https://studypoint.info
Altså en sikret side.

4b)  
Status: 404  

4c)   
200 Successful responses  
300 Redirects  
400 Client errors  
500 Server errors  

5)  
[Link til java](ex1/src/main/java/cookie.java)

6)  
[Link til html](ex1/src/main/webapp/new.html)  
**Browser (GET):** http://localhost:8080/ex1/new.html?hidden=12345678&gender=Hans&gender=Petersen#  

**Browser (POST):** http://localhost:8080/ex1/new.html#  
Ved POST er der et ekstra felt POST data.

[Back to readme](../README.md)  

