
> **Support列表示该存储引擎是否可⽤，DEFAULT值代表是当前服务器程序的默认存储引擎。Comment列是对存储引擎的⼀个描述，英⽂的，将就着看吧。**
> **Transactions列代表该存储引擎是否⽀持事务处理。XA列代表着该存储引擎是否⽀持分布式事务。Savepoints代表着该存储引擎是否⽀持部分事务回滚。**

| Engine             | Support | Comment                                                        | Transactions | XA   | Savepoints |
|:-:|:-|:-|:-|:-|:-|
| MEMORY             | YES     | Hash based, stored in memory, useful for temporary tables      | NO           | NO   | NO         |
| MRG_MYISAM         | YES     | Collection of identical MyISAM tables                          | NO           | NO   | NO         |
| CSV                | YES     | CSV storage engine                                             | NO           | NO   | NO         |
| FEDERATED          | NO      | Federated MySQL storage engine                                 | NULL         | NULL | NULL       |
| PERFORMANCE_SCHEMA | YES     | Performance Schema                                             | NO           | NO   | NO         |
| MyISAM             | YES     | MyISAM storage engine                                          | NO           | NO   | NO         |
| InnoDB             | DEFAULT | Supports transactions, row-level locking, and foreign keys     | YES          | YES  | YES        |
| ndbinfo            | NO      | MySQL Cluster system information storage engine                | NULL         | NULL | NULL       |
| BLACKHOLE          | YES     | /dev/null storage engine (anything you write to it disappears) | NO           | NO   | NO         |
| ARCHIVE            | YES     | Archive storage engine                                         | NO           | NO   | NO         |
| ndbcluster         | NO      | Clustered, fault-tolerant tables                               | NULL         | NULL | NULL       |
