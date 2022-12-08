# treasure

## resolved issues

+ websocket_TEXT_PARTIAL_WRITING: https://bz.apache.org/bugzilla/show_bug.cgi?id=64061
+ zip4j_mac_cant_open: https://github.com/srikanth-lingala/zip4j/issues/86
+ spring_boot_mvc_auto_conf: https://docs.spring.io/spring-boot/docs/2.1.x/reference/html/boot-features-developing-web-applications.html#boot-features-spring-mvc-auto-configuration
+ spring_config_custom_datasource: https://docs.spring.io/spring-boot/docs/2.1.18.RELEASE/reference/html/howto-data-access.html#howto-configure-a-datasource
+ mybatis_multiple_datasource: https://github.com/kazuki43zoo/mybatis-spring-boot-multi-ds-demo/blob/master/src/main/java/com/example/MybatisDemoApplication.java
+ http.proxyHost_not_working_in_resttemplate: https://hc.apache.org/httpcomponents-client-4.5.x/current/httpclient/apidocs/org/apache/http/impl/client/HttpClientBuilder.html, https://cwiki.apache.org/confluence/display/HttpComponents/HttpClientConfiguration
+ spring_boot_2nd_ds_initialization: https://stackoverflow.com/questions/51146269/spring-boot-2-multiple-datasources-initialize-schema/55378247, https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/jdbc/datasource/init/DataSourceInitializer.html, https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/core/io/support/ResourcePatternResolver.html, https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/jdbc/datasource/init/ResourceDatabasePopulator.html, https://gist.github.com/HQidea/8c876466778283f2d8c57212ecfcd8a3
+ access_request-scoped_bean_inside_a_child_process: https://stackoverflow.com/a/38012270
+ read_x-www-form-urlencoded_as_inputstream: https://hongjiang.info/http-application-x-www-form-urlencoded/, https://stackoverflow.com/questions/18406164/order-of-request-parameters-for-content-type-application-x-www-form-urlencoded-i
+ Java home is different. | Please configure the JDK to match the expected one. : https://youtrack.jetbrains.com/issue/IDEA-257065#focus=Comments-27-4649429.0-0 : choose specified jdk rather than JAVA_HOME
+ access dockers persistent volumns on mac:https://timonweb.com/docker/getting-path-and-accessing-persistent-volumes-in-docker-for-mac/

## root causes

+ single-row-deadlock: https://blog.sqlxdetails.com/single-row-deadlock/

+ http2_protocol_error: https://phabricator.wikimedia.org/T209590

+ mysql_index_string_integer: https://stackoverflow.com/questions/16786063/mysql-comparison-of-integer-value-and-string-field-with-index

+ mysql_ddl_metadata_lock: https://dev.mysql.com/doc/refman/5.7/en/innodb-online-ddl-performance.html

+ logback_not_deleting_old_files: https://jira.qos.ch/browse/LOGBACK-162?page=com.atlassian.jira.plugin.system.issuetabpanels%3Acomment-tabpanel&showAll=true, https://github.com/qos-ch/logback/blob/master/logback-core/src/main/java/ch/qos/logback/core/rolling/helper/TimeBasedArchiveRemover.java

+ mysql_rounding_millseconds: https://bugs.mysql.com/bug.php?id=68760, https://dev.mysql.com/doc/refman/5.6/en/fractional-seconds.html
