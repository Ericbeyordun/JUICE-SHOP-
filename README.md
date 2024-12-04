# JUICE-SHOP-
A vulnerability assessment on OWASP Juice Shop using OWASP ZAP to scan for vulnerabilities such as SQLb injection, cross-site scripting (XXS), and authentication weakneasses
*INSTALL NODE JS 22*
+ Type "node -v" to know if node js is installed, if not:
+ sudo apt-get install -y curl
+ sudo curl -fsSL https://deb.nodesource.com/setup_22.x -o nodesource_setup.sh
+ sudo bash nodesource_setup.sh
+ sudo apt-get install -y nodejs
+ Now verify node installation with "node -v"

*INSTALL JUICE SHOP ON UBUNTU*
+ sudo apt install git
+ git clone https://github.com/juice-shop/juice-shop.git --depth 1
+ cd juice-shop
+ npm install
+ If "npm install" did not work, use:
"cd frontend && npm install --legacy-peer-deps && cd .. && npm run build:frontend && (npm run --silent build:server || cd .)"
+ npm start
+ Open browser and go to: http://localhost:3000 or http://ubuntu-ip:3000

*LAUNCH OWASP ZAP FROM KALI*
+ open terminal
+ Type "zaproxy" and press enter to launch ZAP
+ Go to quickstart on ZAP and enter the juice shop url and start attack
+ Vulnerabilities will be listed under "Alerts"

*SQL INJECTION ON JUICE SHOP*
Watch this video:
https://youtu.be/nH4r6xv-qGg?si=10WO_YFUehyxQZwE

*NETWORK SECURITY BEST PRACTICES*
+ Microsegmentation
+ IDS
+ DMZ
+ WAF
+ VPN
+ Encryption 
+ Centralized logging
