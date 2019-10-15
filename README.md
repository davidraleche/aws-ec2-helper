### Create instance ec2 with ssh access
create ec2 instance
create vpc
create subnet - 172.30.0.0/16 or 172.30.3.0/24
create internet gateway
create route tables - 0.0.0.0/0 to internet gateway

### install without verification
yum update -y


### Install new php package
sudo amazon-linux-extras install -y lamp-mariadb10.2-php7.2 php7.2
