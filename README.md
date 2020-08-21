# v2ray docker-compose deployment

## Install docker and docker-compose.

```
curl -fsSL https://get.docker.com | bash -s docker
sudo usermod -aG docker $USER
sudo curl -L "https://github.com/docker/compose/releases/download/1.26.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

## Clone the repo or download the zip file.

```
git clone https://github.com/snakeliwei/ofw.git 
```
```
wget https://github.com/snakeliwei/ofw/archive/master.zip
```

## modify the file for yourself

