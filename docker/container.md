## Containers

---
### Container vs Virtualization

![ContainerVsVirtualization](assets/image/containers-versus-virtual-machines-docker-inc-rightscale.jpg)

Note: 
- Every VM requires an OS
- Every OS consumes resorces (cpu, ram, hd)

--- 

![Container](assets/image/docker-container.png) 


Note: lightweight than vm consumes less resources

---

Container is and isolated and independent instances of user spaces

Note: Kernel namespaces allow to crete isolate instances 

---

```
docker container run --publish 80:80 nginx
```

---

```
docker container run --publish 80:80 --detach nginx 
// to run in background mode 
```
 
---

list the containers

```
docker container list
```

Logs from a container

```
docker container logs webhost
```

---

Process running into a container

```
docker container top webhost
```

---

deleting a container

```
docker container rm webhost
```

```
/// forcing to delete a running container
docker container rm -f webhost
```


