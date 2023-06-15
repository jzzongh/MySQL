# mysql-8.0.33
# 下载解压
# centos7
wget https://github.com/jzzongh/MySQL/releases/download/8.0.33/centos7-mysql-8.0.33.zip  
unzip centos7-mysql-8.0.33.zip  
cd centos7-mysql-8.0.33
# centos8
wget https://github.com/jzzongh/MySQL/releases/download/8.0.33/centos8-mysql-8.0.33.zip  
unzip centos8-mysql-8.0.33.zip  
cd centos8-mysql-8.0.33

# 安装centos7
rpm -ivh mysql-community-common-8.0.33-1.el7.x86_64.rpm  
rpm -ivh mysql-community-client-plugins-8.0.33-1.el7.x86_64.rpm  
rpm -ivh mysql-community-libs-8.0.33-1.el7.x86_64.rpm  
rpm -ivh mysql-community-client-8.0.33-1.el7.x86_64.rpm  
rpm -ivh mysql-community-icu-data-files-8.0.33-1.el7.x86_64.rpm  
rpm -ivh mysql-community-server-8.0.33-1.el7.x86_64.rpm  

# 安装centos8
rpm -ivh mysql-community-common-8.0.33-1.el8.x86_64.rpm  
rpm -ivh mysql-community-client-plugins-8.0.33-1.el8.x86_64.rpm  
rpm -ivh mysql-community-libs-8.0.33-1.el8.x86_64.rpm  
rpm -ivh mysql-community-client-8.0.33-1.el8.x86_64.rpm  
rpm -ivh mysql-community-icu-data-files-8.0.33-1.el8.x86_64.rpm  
rpm -ivh mysql-community-server-8.0.33-1.el8.x86_64.rpm  
