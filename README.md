# Scripts etc to help with cdatx workshop

```
git clone https://github.com/cdatx/workshop.git
cd workshop
```

If you have ubuntu:

```
cp docker /etc/default/docker
service docker restart
```

If you have boot2docker

```
./boot2docker_insecure_registry
```

Any containers that you want from the local registry try this:

```
./fetch ubuntu:trusty
```


