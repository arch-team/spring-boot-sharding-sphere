Rds用户名与密码：
admin
Mwt123456!!

master.cgj1omnlrvhs.us-east-1.rds.amazonaws.com

#DataSourceSettings#
#LocalDataSource: aws-rds-sharding
#BEGIN#
<data-source source="LOCAL" name="aws-rds-sharding" uuid="a1d36d83-6fba-47c1-b691-cf0fff899683">
<database-info product="MySQL" version="5.7.30-log" jdbc-version="4.2" driver-name="MySQL Connector/J" driver-version="mysql-connector-java-8.0.25 (Revision: 08be9e9b4cba6aa115f9b27b215887af40b159e0)" dbms="MYSQL" exact-version="5.7.30" exact-driver-version="8.0">
<extra-name-characters>#@</extra-name-characters>
<identifier-quote-string>`</identifier-quote-string></database-info>
<case-sensitivity plain-identifiers="exact" quoted-identifiers="exact"/>
<driver-ref>mysql.8</driver-ref><synchronize>true</synchronize>
<jdbc-driver>com.mysql.cj.jdbc.Driver</jdbc-driver>
<jdbc-url>jdbc:mysql://master.cgj1omnlrvhs.us-east-1.rds.amazonaws.com :3306</jdbc-url>
<secret-storage>master_key</secret-storage><user-name>admin</user-name><schema-mapping><introspection-scope><node kind="schema"><name qname="@"/><name qname="shardingdb"/><name qname="db_user"/></node></introspection-scope></schema-mapping><working-dir>$ProjectFileDir$</working-dir></data-source>
#END#

