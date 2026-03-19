# 🌐 AWS EC2 Personal Website Hosting

This project demonstrates how I deployed a personal website on AWS EC2 using Nginx. The website was created with the help of Claude (AI assistant) and successfully hosted on a live server.

## 🚀 Live Website

http://13.61.173.132

## 🛠️ Tech Stack

* AWS EC2 (Ubuntu)
* Nginx Web Server
* HTML / CSS
* Linux Commands
* Claude AI (for website creation)

## 📌 Project Overview

In this project, I learned how to launch a cloud server, configure it, and host a live website accessible through a public IP address.

## ⚙️ Steps Performed

1. **Launched EC2 Instance**

   * Used AWS Free Tier
   * Selected Ubuntu OS

2. **Connected to EC2**

   * Used SSH to access the server

3. **Installed Nginx**

   ```bash
   sudo apt update
   sudo apt install nginx
   ```

4. **Started Nginx Server**

   ```bash
   sudo systemctl start nginx
   ```

5. **Deployed Website**

   * Created website using Claude AI
   * Replaced default file in:

     ```
     /var/www/html/index.html
     ```

6. **Configured Security Group**

   * Allowed inbound traffic on:

     * Port 80 (HTTP)

## 🎯 Outcome

* Successfully hosted a live website on AWS EC2
* Gained hands-on experience with cloud computing and web hosting
* Learned server configuration and deployment process

## 📚 Learnings

* Basics of AWS EC2
* Web server setup using Nginx
* File deployment in Linux environment
* Cloud security group configuration

## 👨‍💻 Author

Mayank
GitHub: https://github.com/mayankk7722
