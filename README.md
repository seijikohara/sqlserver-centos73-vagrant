# sqlserver-centos73-vagrant

> SQL Server on CentOS 7.3

## Setup

```bash
# setup VM
vagrant up

# install sql server
vagrant ssh
sudo /opt/mssql/bin/mssql-conf setup
sudo systemctl restart mssql-server
```
