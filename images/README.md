# CONFIGURATION

## Redis

To use redis® it is necessary to create a password

In the Virtual Machine where you run the docker, please use::

```shel
echo "vm.overcommit_memory = 1" >> /etc/sysctl.conf
reboot
```

# TO BUILD

```shell
docker-compose build --pull
```
