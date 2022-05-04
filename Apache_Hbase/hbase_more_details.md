#### Ref:
- https://www.onlineinterviewquestions.com/
- https://viblo.asia/p/hbase-overview-architecture-va-data-flow-63vKj6J6K2R
Question: What is NameSpace in Hbase?
- Answer: 
```
The namespace is used for logical table grouping into a database system.
It helped to resource management, Security, isolation. The syntax of NameSpace is below.
<table namespace>:<table qualifier> .
TL-DR: logical grouping of tables
```

Question: what is HBase table?
- Answer:
```
An HBase table is a multi-dimensional map comprised of one or more columns and rows of data. 
You specify the complete set of column families when you create an HBase table
TL-DR: collection of all rows
```

Question: what is Hbase row?
- Answer:
```
Row—a collection of column families. Column Family—a collection of columns. 
HBase stores data by column family and not row. This makes for faster retrieval of columns since they are located near each other
TL-DR: collection of all column family ( cf )
```

Question: what is Hbase Column Family?
- Answer:
```
Collection of all columns (col)
```

Question: what is Hbase Column?
- Answer:
```
Collection of row-key pairs
```

Question: what is Hbase Cell?
- Answer:
```
row, column, version determine 1 cell in Hbase
```
