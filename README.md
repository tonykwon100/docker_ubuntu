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

* running nginx
```bash
docker pull nginx
docker run -p 80:80 nginx
```


#### References
* [Install Docker Engine on Ubuntu](https://docs.docker.com/engine/install/ubuntu/)
* [우분투에서 도커 설치 및 운용](https://youtu.be/2FiIeVxOUvg)
* [Changing the Docker Image Installation Directory](https://www.baeldung.com/ops/docker-image-change-installation-directory)
