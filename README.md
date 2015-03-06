# Docker firefox

Simple docker container based on ubuntu for running firefox on linux host.

## How to use ?

### 1. Run the container

```bash
# this method share linux host x11 socket
sudo docker run -it -rm -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix mikangali/dff 
```

### 2. Connect with vnc

```
//TODO
```

* Source [tutorial](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)


