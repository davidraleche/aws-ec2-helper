### Create instance ec2 with ssh access

(1) create ec2 instance

(2) create vpc

(3) create subnet - 172.30.0.0/16 or 172.30.3.0/24

(4) create internet gateway

(5) create route tables - 0.0.0.0/0 to internet gateway



### Install without verification
yum update -y


### Install new php package
sudo amazon-linux-extras install -y lamp-mariadb10.2-php7.2 php7.2
