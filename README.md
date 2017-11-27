Ganeti External Storage for HPe 3PAR
------------------------------------

Warning This is a WIP !

Install :
---------

install required packages and clone this repo into **/usr/share/ganeti/extstorage/**

<code>
apt install python-eventlet python-paramiko apt install python-requests
cd /usr/share/ganeti/extstorage/
git clone https://github.com/DSI-Universite-Rennes2/hp3par.git
</code>

Ensure REST Api is enabled on HPe 3PAR

Config :
--------

edit **3par.conf** file and copy it into **/etc/ganeti/extstorage/**
<code>
mkdir /etc/ganeti/extstorage/
cp 3par.conf /etc/ganeti/extstorage/
vim /etc/ganeti/extstorage/3par.conf
</code>