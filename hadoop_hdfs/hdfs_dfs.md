## Ref: 
- https://sparkbyexamples.com/apache-hadoop/hadoop-hdfs-dfs-commands-and-starting-hdfs-dfs-services/
- https://www.edureka.co/community/49603/how-setrep-command-is-used-and-what-is-the-description-to-this
- 
Note: user in hdfs map with user in linux, same for group


- setrep command:
This HDFS command is used to change the replication factor of a file. If the entered path is a directory, then this command changes the replication factor of all the files present in the directory tree rooted at the path provided by user recursively.

HDFS setrep Command usage:
```
setrep [-R] [-w] rep <path>
```
HDFS setrep Command Example
```
hdfs dfs -setrep -w 3 /user/dataflair/dir1
```
Here, the -w flag requests that the command waits for the replication process to get completed. This may likely take a very long time to get completed.

The -R flag is accepted for backward compatibility. It does not make any changes.


