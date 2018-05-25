## Images

---
### How to create a docker image? 

- Using a docker file.
- Using a container.

---
#### Docker file

```
FROM alpine

# the executable
ENTRYPOINT ["sleep"]

# the default arguments
CMD ["10000"]

```


