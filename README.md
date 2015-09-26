# for CentOS7.x

## INSTALL

```
cd /usr/local/src/
git clone https://github.com/mykysyk/nspawn.git
mkdir -p /var/lib/container
ln -sf /usr/local/src/nspawn/nspawnctl /usr/local/bin/nspawnctl
```

## USAGE

```
--- USAGE ---
 /usr/local/bin/nspawnctl create    [centos5|centos6|centos7] [CONTAINER_NAME] [CONTAINER_PASSWORD]
 /usr/local/bin/nspawnctl overlay   [centos5|centos6|centos7] [CONTAINER_NAME] [CONTAINER_PASSWORD]
 /usr/local/bin/nspawnctl console   [CONTAINER_NAME]
 /usr/local/bin/nspawnctl list
 /usr/local/bin/nspawnctl master-list
 /usr/local/bin/nspawnctl master-create  [centos5|centos6|centos7]
 /usr/local/bin/nspawnctl start     [CONTAINER_NAME]
 /usr/local/bin/nspawnctl autostart [CONTAINER_NAME]
 /usr/local/bin/nspawnctl autostart --disable [CONTAINER_NAME]
 /usr/local/bin/nspawnctl autostart --list
 /usr/local/bin/nspawnctl shutdown  [CONTAINER_NAME]
 /usr/local/bin/nspawnctl destroy   [CONTAINER_NAME]
 /usr/local/bin/nspawnctl undefine  [CONTAINER_NAME]
 /usr/local/bin/nspawnctl show      [CONTAINER_NAME]
