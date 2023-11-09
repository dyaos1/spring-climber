## ACCESSING DATA MYSQL
https://spring.io/guides/gs/accessing-data-mysql/

mysql> revoke all on db_example.* from 'springuser'@'%';

mysql> grant select, insert, delete, update on db_example.* to 'springuser'@'%';