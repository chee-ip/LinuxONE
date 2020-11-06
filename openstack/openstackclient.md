### Install openstack client (Version >= T) on RHEL7

##

- Install Python3

```
yum install python3 python3-devel
```

- Install dependancy packages
```
yum install openssl-devel libffi-devel
```

- Install openstack client
```
pip3 install python-openstackclient
```