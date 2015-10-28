# adite/volume_container
---
## tescom's Docker Volume Container 
![tescom](https://en.gravatar.com/userimage/96759029/aa4308f795041de37cc2fedf0d1071ca?size=128)

## IMAGE FROM
Debian

## Volume Information
```shell
/data
```

## USAGE
```shell
$ sudo docker run -i -t --volumes-from adite/volume_container -v ${local_directory}:/data
```
