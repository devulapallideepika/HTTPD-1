# Deploying Application on Ec2 instance using HTTPD 
- create an ec2 instance and connect to git bash terminal.
- Allow the inbound rule of security group with port range 80.As http by default runs on port 80.

![image](https://github.com/devulapallideepika/HTTPD-1/assets/129947829/9ab4ce09-6b34-44b9-962c-a2ea941d1296)

- sudo yum install git - command to install git.

![image](https://github.com/devulapallideepika/HTTPD-1/assets/129947829/876fd2f0-71ed-447a-9857-c281e883bba8)

- sudo yum install httpd - command to install httpd.
- sudo systemctl start httpd -command to start httpd.
- sudo systemctl enable httpd - command to enable httpd.
- sudo systemctl status httpd - command to check if httpd is running or not.

![image](https://github.com/devulapallideepika/HTTPD-1/assets/129947829/4e60830f-c8c4-48d0-ab83-acac0a33436f)

- Change the directory to  /var/www/html.
- It is the default directory of httpd.
- sudo git clone <URL> to copy the repository.
- Copying the repository in /var/www/html directory.
- Now copy the public ip address and paste it on the browser.

![image](https://github.com/devulapallideepika/HTTPD-1/assets/129947829/b82ec237-2319-4645-bb08-31c60458b7a0)

![image](https://github.com/devulapallideepika/HTTPD-1/assets/129947829/69d5ecd4-89d8-4643-bef2-c834926fa902)
- Hosted this website on ec2 instance.
