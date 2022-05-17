- Create table with Key range: 000 -> 999
```
create 'hbase_tbl_dev', 'cf', {SPLITS => ['050','100','150','200','250','300','350','400','450','500','550','600','650','700','750','800','850','900','950']}
alter 'hbase_tbl_dev', { NAME => 'cf', COMPRESSION => 'SNAPPY' }
alter 'hbase_tbl_dev', {METADATA => {'SPLIT_POLICY' => 'org.apache.hadoop.hbase.regionserver.DisabledRegionSplitPolicy'}}
```
