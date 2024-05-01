# Duplicati docker setup for custom vps

See [https://hub.docker.com/r/linuxserver/duplicati](https://hub.docker.com/r/linuxserver/duplicati) as reference

As recommanded, the web GUI is accessible only from localhost.
So use port forwarding as follow to access it

`ssh -L 8200:localhost:8200 paolo@REMOTE_HOST_ADRESS`
