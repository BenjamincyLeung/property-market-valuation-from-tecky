# Env Set-up

## 1. python3.9

ubuntu:
```bash
sudo apt install python3.9
sudo apt install python3.9-venv
python3.9 -m venv myenv
source myenv/bin/activate
sudo apt install python3-pip
pip list
pip install -r requirements.txt
pip freeze > requirements.txt
```

local:
```bash
python -m venv myenv
source myenv/bin/activate
pip install --upgrade pip
pip list
pip install -r requirements.txt
pip freeze > requirements.txt
```
&nbsp;

## 2. Ubuntu set-up (if you are using ubuntu:gcp/aws)
```bash
sudo apt install nodejs
sudo apt install npm
sudo npm install -g n
sudo n latest
npm update
//reopen terminal
node -v
npm update
```

## 3.1 React Set-up by ubuntu

```bash
cd my-react-app
sudo npm install -g yarn
yarn install
```

## 3.2 React Set-up by local
```bash
cd my-react-app
yarn init -y
yarn install
```
Or you could edit or delete the directory
 ```bash 
rm -rf my-react-app
``` 
directory and make your own. And remind us what needed to be set-up

&nbsp;

## 4. Docker

ubuntu:
```bash
sudo apt install docker.io
sudo apt install docker-compose
sudo gpasswd -a ${USER} docker
sudo reboot
```

local: just download link:
https://docs.docker.com/desktop/mac/install/

then run the docker 
```bash
docker-compose up -d
```

&nbsp;

