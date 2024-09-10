# dockerfile Description
creates using a base image of "alpine:latests"
sends command to echo text, in this case "Hello, Captain"

make sure your dockerfile is in root, and its the only dockerfile available

run using 
```
sudo docker build .
```

sudo - Runs as super user
docker build - build docker from dockerfile
. - specifies the path, period meaning exactly where you currently are in directory. 

https://roadmap.sh/projects/basic-dockerfile