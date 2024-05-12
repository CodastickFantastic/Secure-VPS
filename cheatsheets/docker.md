# Docker Cheatsheet for Novice
Following file contains basic information abuot Docker for Novice. \
You can use it to enhance your knowledge about Docker usuage. 

## What is Docker?
> Docker is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly. With Docker, you can manage your infrastructure in the same ways you manage your applications. By taking advantage of Docker's methodologies for shipping, testing, and deploying code, you can significantly reduce the delay between writing code and running it in production. [^1]

## Docker Cheatsheet
Following section shows basics Docker commands that you will use the most during your VPS maintains.\
Cheatsheet consists of:
1. Container Operations
2. Images Operations
3. Networks Operations
### Containers Operations
**List all Containers**
```bash
docker container ls -a
```
**Remove Container**
```bash
docker container rm <container-id>
```

[^1]: https://docs.docker.com/get-started/overview/
