# Documentation 🙂

### **Problem 1:** Cannot unzip file
  
  Solution 1: Make sure you put sudo in front of command
  
  
  <img width="460" height="35" alt="1" src="https://github.com/user-attachments/assets/244df87e-7a7d-47d1-95f8-bfef23dd104d" />

  
  Solution 2: Install unzip command using `sudo apt install unzip`
  

<img width="460" height="58" alt="2" src="https://github.com/user-attachments/assets/3d31609d-7e3c-4753-8067-6ca701c97a7e" />

---


### **Problem 2:** Wordpress site timing out and not loading
 <img width="1159" height="539" alt="3" src="https://github.com/user-attachments/assets/0e8c0be4-f58d-4eab-9a5d-edb263a981ce" />

  Solution 1: Try `http://ipaddress/librar/wp-admin/install.php`

  Solution 2: Make sure that your inputs from 
```  
create user 'wordpress'@'localhost' identified by 'XXXXXXXXX';
create database wordpress;
grant all privileges on wordpress.* to 'wordpress'@'localhost';
show databases;
\q
```
 Match exactly the inputs into `wp-config.php`
