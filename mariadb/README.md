MariaDB [(none)]> create user 'exporter'@'%' identified by '123123a@';
MariaDB [(none)]> grant process, replication client on *.* to 'exporter'@'%';    
MariaDB [(none)]> grant select on performance_schema.* to 'exporter'@'%';
