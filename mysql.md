# 2018年10月15日记录

### 连接mysql 

```
1.连接mysql mysql -uroot -ppassword
```

### mysql 常见命令

```mysql
1.查看当前所有的数据
	show databases;
2.打开指定的库
	use 库名
3.查看当前库所有的表
	show tables;
4.查看当前库所有的表
	show tables from 库名;
5.创建表
	create table 表名(
    	列名   列类型
        列名   列类型
        ...
    )
6.查看表结构
	desc 表名;
	

7.查看服务器的版本
	方式一：登录到sql服务器 
	select version();
	方式二：没登录
	mysql --version
	mysql --V
	

```

### MySql语法规范

```mysql
1. 不区分大小写，但是建议关键字大写，表名、列名小写
2. 每条命令最好用分好结尾
3. 每条命令根据需要，可以缩进或者换行
```



## typora 编辑，注意下载此编辑器