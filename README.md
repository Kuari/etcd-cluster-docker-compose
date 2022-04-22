# etcd-cluster-docker-compose

Use the latest version of etcd, directly pull the official image to run.Will run 3 nodes, the configuration can be edited in the .env file.



## Usage

### 1. update configuration

Edit the `.env` file and modify the run configuration.

### 2. create a network

```
docker network create etcd-net
```

### 3. run

```
docker-compose up -d
```



## Other

[official documentation](https://etcd.io/docs/v2.3/docker_guide/#running-a-3-node-etcd-cluster)