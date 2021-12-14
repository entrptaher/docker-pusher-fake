# docker-pusher-fake
Docker image with pusher-fake binary installed

Install docker

```
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
```

Let user run docker as root:
```
sudo usermod -aG docker $USER
newgrp docker
```

Install Docker-compose

```
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

Run:

```
docker-compose up
```