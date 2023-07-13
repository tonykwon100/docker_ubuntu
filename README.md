# docker_ubuntu


#### Install docker on ubuntu

* add user for docker
```bash
tony@kwon:~$ sudo usermod -aG docker tony
tony@kwon:~$ sudo service docker restart
tony@kwon:~$ docker ps
```

** IF PERMISSION DENIED!
```bash
sudo groupadd -f docker
sudo usermod -aG docker $USER
newgrp docker
```

#### References
* [Install Docker Engine on Ubuntu](https://docs.docker.com/engine/install/ubuntu/)
* 
