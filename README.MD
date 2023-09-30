###VPC

This module is going to create
*VPC
*Internet Gateway
* 2 Public subnets
* 2 Private Subnets
* 2 Database Subnets
### Inputs
* cidr block(Required) - User has to provide cidr block
* enable_dns_hostnames(Optional) - User can provide enable_dns_hostnames, ***default is true***
* enable_dns_support(Optional) - User can provide enable_dns_support, ***default is true***
* common_tags(Optional) - User can provide common tags for all resource, default is empty
* VPC_tags(Optional) - User can provide vpc tags for all resource, default is empty
* igw_tags(Optional) - User can provide igw tags for all resource, default is empty
* Public_subnet_cidr(Required) - user must provide a list of 2 public subnet CIDR.
* Public_subnet_names(Required) - user must provide a list of 2 public subnet CIDR.
* azs(Required) - user must provide 2 az
* Private_subnet_cidr(Required) - user must provide a list of 2 private subnet CIDR.
* Private_subnet_names(Required) - user must provide a list of 2 private subnet CIDR.
* Database_subnet_cidr(Required) - user must provide a list of 2 database subnet CIDR.
* Database_subnet_names(Required) - user must provide a list of 2 database subnet CIDR.



