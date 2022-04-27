### Ref: 
- https://data-flair.training/blogs/hadoop-hdfs-disk-balancer/

- How much type for writing data when having multiple disks: 2 policies
+ Round-Robin policy
+ Available space policy

- Step for remove disk:
1. Insert host into dfs.exclude
2. refreshNodes
3. Wait for decommission finish
4. stop data node 
5. remove disk config in `dfs.datanode.data.dir`
6. start data node
7. refresh Nodes again
