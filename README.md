# for CentOS7.x

## INSTALL

cd /usr/local/src/nspawn/
git clone https://github.com/mykysyk/nspawn.git  
ln -sf /usr/local/src/nspawn/nspawnctl /usr/local/bin/nspawnctl

## USAGE 

--- USAGE ---
 /usr/local/bin/nspawn-ctl create    [centos5|centos6|centos7] [CONTAINER_NAME] [CONTAINER_PASSWORD]
 /usr/local/bin/nspawn-ctl console   [CONTAINER_NAME]
 /usr/local/bin/nspawn-ctl list
 /usr/local/bin/nspawn-ctl master-list
 /usr/local/bin/nspawn-ctl start     [CONTAINER_NAME]
 /usr/local/bin/nspawn-ctl autostart [CONTAINER_NAME]
 /usr/local/bin/nspawn-ctl autostart --disable [CONTAINER_NAME]
 /usr/local/bin/nspawn-ctl autostart --list
 /usr/local/bin/nspawn-ctl shutdown  [CONTAINER_NAME]
 /usr/local/bin/nspawn-ctl destroy   [CONTAINER_NAME]
 /usr/local/bin/nspawn-ctl undefine  [CONTAINER_NAME]
 /usr/local/bin/nspawn-ctl show      [CONTAINER_NAME]
