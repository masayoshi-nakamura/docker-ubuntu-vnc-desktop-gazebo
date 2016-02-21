docker-ubuntu-vnc-desktop
=========================

[![Docker Pulls](https://img.shields.io/docker/pulls/dorowu/ubuntu-desktop-lxde-vnc.svg)](https://hub.docker.com/r/dorowu/ubuntu-desktop-lxde-vnc/)
[![Docker Stars](https://img.shields.io/docker/stars/dorowu/ubuntu-desktop-lxde-vnc.svg)](https://hub.docker.com/r/dorowu/ubuntu-desktop-lxde-vnc/)

From Docker Index
```
docker pull dorowu/ubuntu-desktop-lxde-vnc
```

Build yourself
```
git clone https://github.com/fcwu/docker-ubuntu-vnc-desktop-gazebo.git
docker build --rm -t dorowu/ubuntu-desktop-lxde-vnc docker-ubuntu-vnc-desktop-gazebo
```

Run
```
docker run -i --env="QT_X11_NO_MITSHM=1"  -t -p 6080:6080 dorowu/ubuntu-desktop-lxde-vnc-gazebo
```

Browse http://127.0.0.1:6080/vnc.html


Troubleshooting
==================

1. boot2docker connection issue, https://github.com/fcwu/docker-ubuntu-vnc-desktop/issues/2


License
==================

desktop-mirror is under the Apache 2.0 license. See the LICENSE file for details.
