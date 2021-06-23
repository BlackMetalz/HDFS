### HBase Architecture is basically a column-oriented key-value data store and also it is the natural fit for deploying as a top layer on HDFS because it works extremely fine with the kind of data that Hadoop process.
Moreover, when it comes to both read and write operations it is extremely fast and even it does not lose this extremely important quality with humongous datasets.
There are 3 major components of HBase Architecture:

1. Zookeeper
2. HMaster server
3. Region servers

![image](https://user-images.githubusercontent.com/3434274/123074440-7ec90c80-d441-11eb-9bab-6ceb89113dd1.png)
