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


3.Nginx installation
1. sudo apt install nginx -y
2. sudo systemctl status nginx
3. sudo systemctl restart nginx
