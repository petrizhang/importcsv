# importcsv
将csv文件导入mysql数据库的小工具，依赖bash
# 1、安装
  在本文件夹内运行如下命令安装:  
  sudo ./install.sh  
# 2、命令参数
| 参数 | 解释 |
| ------------- |:-------------| 
|  -f filepath   |   要导入的csv文件  |
|  -D db_name    |   要连接的数据库名称 |  
|  -t table_name  |  要导入到的目标表名称  |
| -i ignore_lines | 忽略csv文件的前ignore_lines行  |
# 3、功能
  将指定的csv文件导入指定数据库的指定表（需自行建表，若表的格式与csv不符会报错）。  
# 4、注意  
  本程序依赖bash，其他shell无法正常执行。  
