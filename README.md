# kolla-images
Pull dockerhub kolla images to aliyun registry by github Actions.

## Get image list
```
for i in $(cat images.txt);do echo "\"kolla/ubuntu-binary-$i:train\":\"registry.cn-guangzhou.aliyuncs.com/lunwei/ubuntu-binary-$i:train\"",;done
```
