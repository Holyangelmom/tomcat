# 配置部署

**1、解压**

tar -zxvf apache-tomcat-7.0.78.tar.gz

**2、移动**

mv apache-tomcat-7.0.78 /usr/local/tomcat

**3、配置环境变量**

vim /etc/profile

追加如下内容\(需提前安装jdk\):

export TOMCAT\_HOME=/usr/local/tomcat7

export CATALINA\_HOME=/usr/local/tomcat7

source /etc/profile

**可能存在的问题：**



