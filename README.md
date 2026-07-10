# aws-devops-assingment
1.EC2 setup step
1. login AWS console.
2. Go to EC2 - Launch instance.
3. Name: ubundtu
4. Select ubuntu server.
5. Instance Type: t2.micro.
6. Create a new key pair and download .pem fle.
7. Creat security group : ubuntu-sg
    SSh(port 22) - My IP
    HTTP(port 80) -Anywhere
8. Click Launch Instance.


2.linux commands

1. chmod 400 my-key.pem
2. ssh i my-key.pem
3. ubuntu@<public-ip>
4. sudo apt update
5. sudo apt updrade -y
6. df
7. free
8. top
   

3.Nginx installation
1. sudo apt install nginx -y
2.sudo systemctl status nginx
3. sudo systemctl restart nginx

4.Problem faced 
1. SSH permission deniend issue.
2. Nginx service not starting.

5. Learning
1. EC2 instance creation.
2. linux basic commands.
3. Git and GitHub workflow.

6. Time Taken
1. EC2 setup 15-minutes.
2. Linux Tasks- 20 minutes.
3. website Deployment- 15 minutes.
4. GitHub upload- 15 minutes.
5. documentation- 25 minutes.
6. sudo systemctl status nginx
7. sudo systemctl restart nginx
