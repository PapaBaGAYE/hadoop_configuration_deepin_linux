**core-site.xml**
```
<configuration>
  <property>
    <name>fs.defaultFS</name>
    <value>hdfs:localhost:9000</value>
  </property>
</configuration>
```

**hdfs-rbf-site.xml**
```
<configuration>
  <property>
    <name>dfs.replication</name>
    <value>1</value>
  </property>
</configuration>
```

**mapred-site.xml**
```
<configuration>
  <property>
    <name>mapreduce.framework.name</name>
    <value>yarn</value>
  </property>
</configuration>
```

**yarn-site.xml**
```
<configuration>
  <property>
    <name>yarn.nodemanager.aux-services</name>
    <value>mapreduce_shuffle</value>
  </property>
</configuration>
```

**@papabagaye**
