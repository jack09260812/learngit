title: S3服务中oozie配置
categories: [CDH,S3]
date: 2017-10-24
---
```
hadoop credential create fs.s3a.access.key -provider jceks://hdfs/tmp/file.jceks -value BBBA74VJ69J8I4N0GW3O

hadoop credential create fs.s3a.secret.key -provider jceks://hdfs/tmp/file.jceks -value eNKTsutRmHR8HHM03Mx3xT6ctaW3Fd+PX75KGatk
```