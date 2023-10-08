## Task x) Homework Report Links
1. https://github.com/Abrar76/h1-First-steps
2. https://github.com/Abrar76/h2-Spiderweb/blob/main/h2-Spiderweb.docx
3. https://github.com/Abrar76/h3-Assignment/blob/main/h3%20_Should%20Tero%20wear%20a%20helmet.docx
4. https://github.com/Abrar76/h4_ETAOIN/blob/main/h4_ETAOIN.docx
5. https://github.com/Abrar76/h5-September2023/blob/main/h5.md
6. https://github.com/Abrar76/h6-A-Nynomous/blob/main/h6.md

## y) Presentation cross evaluation
It was done in Moodle
## a) Firewall. Install a firewall on Linux and block all ports you don't need to be open.
1. Install update
 sudo apt-get update
 ![image](https://github.com/Abrar76/h7-Final-countdown/assets/79007051/c6353158-8938-4200-a6ee-8ef2b233a35e)
   
3. After this Installing Firewall. Allowing SSH on Port 22 before enabling firewall
  sudo apt-get install ufw
  sudo ufw allow 22/tcp
  sudo ufw enable

![image](https://github.com/Abrar76/h7-Final-countdown/assets/79007051/f7b22e0d-b53a-453a-ab51-f8f956c26237)

## b) Ssherver. Install OpenSSH server and connect to it

First installing ssh
![image](https://github.com/Abrar76/h7-Final-countdown/assets/79007051/3ca0e39b-0b97-4062-a080-f3ab7a824d92)

chekc for user name on the computer, then start SSH connection and then connect to SSH server.
- whoami
- sudo systemctl start ssh
- ssh username@localhost

![image](https://github.com/Abrar76/h7-Final-countdown/assets/79007051/409bfea4-0169-4b7c-b26e-3026b3fbccac)

Create new user with strong bad password
sudo adduser user

![image](https://github.com/Abrar76/h7-Final-countdown/assets/79007051/635893f3-4ac6-4667-a065-2aba6425786d)

Now Connecting new user to the ssh server
ssh user@localhost

![image](https://github.com/Abrar76/h7-Final-countdown/assets/79007051/0e173c6e-50f5-4e04-80e6-469b44b7773a)

Checking how many users are in the server
- who -a

![image](https://github.com/Abrar76/h7-Final-countdown/assets/79007051/f9e7dfd6-ae74-4dd1-a76d-7ba96e02c100)

command Ctrl + D to exit the server

![image](https://github.com/Abrar76/h7-Final-countdown/assets/79007051/8e45ebb7-891a-423d-8593-60e5cef6b5ef)

Done.!!








   


 
