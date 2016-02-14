docker-ubuntu-vnc-desktop
=========================

From Docker Index
```
docker pull babim/ubuntu-novnc
```

Build yourself
```
git clone https://github.com/babim/docker-ubuntu-vnc-desktop.git
docker build --rm -t babim/ubuntu-novnc docker-ubuntu-vnc-desktop
```

Run
```
docker run -i -t -p 6080:6080 babim/ubuntu-novnc
```

Browse http://127.0.0.1:6080/vnc.html

<img src="https://raw.github.com/babim/docker-ubuntu-vnc-desktop/master/screenshots/lxde.png" width=400/>


Troubleshooting
==================

1. boot2docker connection issue, https://github.com/babim/docker-ubuntu-vnc-desktop/issues/2


License
==================

desktop-mirror is under the Apache 2.0 license. See the LICENSE file for details.
