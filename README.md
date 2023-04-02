# What I improved

* add ranger HiveMetaStore plugin base [Ranger-HiveMetaStore-Plugin](https://github.com/insightlake/Ranger-Metastore-Plugin)
* update [Ranger-HiveMetaStore-Plugin](https://github.com/insightlake/Ranger-Metastore-Plugin) version to ranger-2.3, and support to store audit log in elasticsearch





# Build

```shell
git clone https://github.com/weaksloth/ranger.git
```



```shell
mvn clean package -Dmaven.wagon.http.ssl.insecure=true -Dmaven.wagon.http.ssl.allowall=true -Dmaven.wagon.http.ssl.ignore.validity.dates=true  -Drat.skip=true -Dmaven.test.skip=true -Denforcer.skip -Dcheckstyle.skip -Djacoco.skip=true -Dfindbugs.skip=true -DskipTests=true
```

then you can get tar files in target directory:

```shell
-rw-r--r-- 1 chen chen 518814981  4月 2日 16:08 ranger-2.3.0-admin.tar.gz
-rw-r--r-- 1 chen chen  41569018  4月 2日 16:08 ranger-2.3.0-atlas-plugin.tar.gz
-rw-r--r-- 1 chen chen  36505541  4月 2日 16:08 ranger-2.3.0-elasticsearch-plugin.tar.gz
-rw-r--r-- 1 chen chen  36983064  4月 2日 16:07 ranger-2.3.0-hbase-plugin.tar.gz
-rw-r--r-- 1 chen chen  35542411  4月 2日 16:07 ranger-2.3.0-hdfs-plugin.tar.gz
-rw-r--r-- 1 chen chen  35341931  4月 2日 16:07 ranger-2.3.0-hive-plugin.tar.gz
-rw-r--r-- 1 chen chen  54593660  4月 2日 16:08 ranger-2.3.0-kafka-plugin.tar.gz
-rw-r--r-- 1 chen chen 195212549  4月 2日 16:08 ranger-2.3.0-kms.tar.gz
-rw-r--r-- 1 chen chen  49245794  4月 2日 16:07 ranger-2.3.0-knox-plugin.tar.gz
-rw-r--r-- 1 chen chen  34480696  4月 2日 16:08 ranger-2.3.0-kylin-plugin.tar.gz
-rw-r--r-- 1 chen chen     34220  4月 2日 16:08 ranger-2.3.0-migration-util.tar.gz
-rw-r--r-- 1 chen chen  41241695  4月 2日 16:08 ranger-2.3.0-ozone-plugin.tar.gz
-rw-r--r-- 1 chen chen  55216042  4月 2日 16:08 ranger-2.3.0-presto-plugin.tar.gz
-rw-r--r-- 1 chen chen  16254236  4月 2日 16:08 ranger-2.3.0-ranger-tools.tar.gz
-rw-r--r-- 1 chen chen    905882  4月 2日 16:08 ranger-2.3.0-schema-registry-plugin.jar
-rw-r--r-- 1 chen chen     37579  4月 2日 16:08 ranger-2.3.0-solr_audit_conf.tar.gz
-rw-r--r-- 1 chen chen     40595  4月 2日 16:08 ranger-2.3.0-solr_audit_conf.zip
-rw-r--r-- 1 chen chen  36091035  4月 2日 16:08 ranger-2.3.0-solr-plugin.tar.gz
-rw-r--r-- 1 chen chen  34719120  4月 2日 16:08 ranger-2.3.0-sqoop-plugin.tar.gz
-rw-r--r-- 1 chen chen   6340500  4月 2日 16:08 ranger-2.3.0-src.tar.gz
-rw-r--r-- 1 chen chen  49582337  4月 2日 16:07 ranger-2.3.0-storm-plugin.tar.gz
-rw-r--r-- 1 chen chen  30119584  4月 2日 16:08 ranger-2.3.0-tagsync.tar.gz
-rw-r--r-- 1 chen chen  19652021  4月 2日 16:08 ranger-2.3.0-usersync.tar.gz
-rw-r--r-- 1 chen chen  33384352  4月 2日 16:08 ranger-2.3.0-yarn-plugin.tar.gz
```



# Usage

1. see ranger offical doc in wiki
2. see blog of mine: [ranger-blog](http://www.yangc.top/archives/apache-ranger)

# Reference

https://github.com/insightlake/Ranger-Metastore-Plugin