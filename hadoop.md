# hadoop

格式化

```bash
$ bin/hdfs namenode -format
```



启动节点

```bash
$ sbin/start-dfs.sh
```



验证是否成功

```bash
$ jps
3053 SecondaryNameNode
2644 NameNode
3177 Jps
2829 DataNode
```

```
http://192.168.16.37:50070   # NameNode端口
8020是使用时的端口
```



停止节点

```
$ sbin/stop-dfs.sh
```



命令介绍

hdfs dfs

hadoop fs -ls <path>

hadoop fs -put <files>

hadoop fs -text <full file path>   #  print content

hadoop fs -get <full path>



