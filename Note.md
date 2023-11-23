need to install Docker on Jenkins host

need PAT for dockerhub and Github

sudo chmod 666 /var/run/docker.sock

add jenkins and bitnami right to docker group
$ sudo usermod -aG docker jenkins
$ sudo usermod -aG docker bitnami

test 

$ sudo su - jenkins
$ docker login

sudo su - jenkins
$ docker login
Authenticating with existing credentials...
WARNING! Your password will be stored unencrypted in /bitnami/jenkins/home/.docker/config.json.
Configure a credential helper to remove this warning. See
https://docs.docker.com/engine/reference/commandline/login/#credentials-store

Login Succeeded

