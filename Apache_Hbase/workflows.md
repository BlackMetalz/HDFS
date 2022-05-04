### 1. Hbase Architecture : Client vs Hbase and HMaster

![image](https://user-images.githubusercontent.com/3434274/166670029-e0b3cd3b-a61f-4ecb-b16d-6459578bc7ab.png)

- Client connect with zookeeper endpoint, retrieve list of region servers
- Client use read/write data operation to Region Servers after get list of region servers
- Client rarely needs HMaster
- while HMaster asssign region to RegionServers and check health of RegionServers 
