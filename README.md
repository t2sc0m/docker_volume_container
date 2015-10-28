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
### Start Volume Container
```shell
$ sudo docker run -d -name av adite/volume_container:v1 -v ${local_share_directory}:/data
```

### Use Volume Container
```shell
$ sudo docker run -d --volumes-from av ${container_name}
```
