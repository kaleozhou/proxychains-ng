db2 catalog tcpip node DB2QING remote 172.16.3.51 server 50000
db2 list node directory
db2 catalog DB CTDB as DB2QING01 at node DB2QING
db2 list db directory
./proxychains4 db2 connect to DB2CTDB user db2inst1 using abc123

