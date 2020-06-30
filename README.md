# Prerequisite
1. Virtual box https://www.virtualbox.org/
- This program used v6.1
2. Installing Vagrant https://www.vagrantup.com/
- This program used v2.2.9

# User Installation:
1. Clone this repo
2. Running VM in starter-code
```bash
vagrant up
```
Starts up VM server (will take some time)
3. Go into app
```bash
vagrant ssh app
```
4. Go to app
```bash
cd /home/ubuntu/app
```
5. Start npm
```bash
npm start
```
6. Check if running
- Go to browser
- type in http://192.168.10.100:3000/posts
You should see some posts :)
