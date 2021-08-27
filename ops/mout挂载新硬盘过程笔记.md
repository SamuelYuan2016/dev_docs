## 查看分区
```shell
fdisk -l
```

## 查看卷信息
```
lvdisplay  
![image](https://user-images.githubusercontent.com/23330469/131088321-2032a41d-1479-4138-9916-fea5707b2587.png)
sudo mount /dev/centos/home /mnt
sudo mkdir /root/recovery
cd /mnt/root/
cp -R . /root/recovery
