FROM tomcat
MAINTAINER youji@ebay.com

ADD xxl-job-admin/xxl-job-admin.war /usr/local/tomcat/webapps/xxl-job-admin.war
ADD xxl-job-executor-samples/xxl-job-executor-sample-spring.war /usr/local/tomcat/webapps/xxl-job-executor.war

CMD ["catalina.sh", "run"]