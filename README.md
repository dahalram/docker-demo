# docker-demo

## Remove existing version of docker files
```sudo yum remove docker docker-client docker-client-latest docker-common docker-latest docker-latest-logrotate docker-logrotate docker-selinux docker-engine-selinux docker-engine```

## Install latest version of Docker
```sudo yum install -y yum-utils device-mapper-persistent-data lvm2```

```sudo yum-config-manager — add-repo https://download.docker.com/linux/centos/docker-ce.repo```

```sudo yum install docker```

## Start docker and run test script
```sudo systemctl start docker```

```sudo docker run hello-world```
