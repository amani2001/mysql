# mysql
error of install and start server

1. [[error code 1045](https://www.jb51.net/article/119712.htm)]:MYSQL报错信息是ERROR 1045 (28000): Access denied for user 'root'@'localhost' (using password: YES)
2. [[MySQL服务正在启动后自动停止，且服务没有报告任何错误](https://blog.csdn.net/u011583025/article/details/50936145)]，可以查看programData目录下的mysql的数据文件夹下是否有data目录，若没有输入，mysqld -initialize
