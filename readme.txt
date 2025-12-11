谁家好人写日记啊
show index from table;
create index index_name on table(cloum)
drop indecx indexname from table;
create index indexname on table()
drop index indexname from table;
set autocommit =0 禁止自动提交事务
set autocommit=1  开启自动提交事务；
MySQL 安装后默认 autocommit = 1，可在 my.cnf/my.ini 中配置全局默认值（永久生效）：仅 DML 操作（INSERT/UPDATE/DELETE）受影响，DDL 操作（CREATE/DROP/ALTER）会隐式提交事务，即使 autocommit = 0 也会立即生效




20251211
