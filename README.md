# meteor [![Build Status](https://travis-ci.org/incu6us/meteor.svg)](https://travis-ci.org/incu6us/meteor) [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/meteor-cd/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

The lightweight and quick continuous delivery tool 

![meteor](https://raw.githubusercontent.com/incu6us/meteor/master/examples/images/meteor.png)

### Installation
##### build:
```
go build .
```

##### start command:
```
./meteor -conf meteor.conf
```

##### start with **systemd**:

```
mkdir /opt/meteor
cp -r {meteor,meteor.conf,tasks} /opt/meteor/
cp examples/systemd/meteor.service /etc/systemd/system/
systemctl daemon-reload
systemctl enable meteor
systemctl start meteor
```

