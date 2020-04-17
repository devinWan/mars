# 项目模板生成

https://blog.csdn.net/xwnxwn/article/details/52529417

## 1.创建一个多模块的模板项目

## 2.进入到父pom目录下,执行mvn archetype:create-from-project

##3.在target目录中的archetype目录生成模板

1. 使用mvn clean install 安装本地仓库中
2. 命令执行
mvn archetype:generate -DarchetypeCatalog=local -DarchetypeGroupId=com.mars -DarchetypeArtifactId=mars-template-parent-archetype -DarchetypeVersion=0.0.1-SNAPSHOT -DgroupId=com.mars -DartifactId=sso -Dversion=1.0.0-RELEASE -Dpackage=com.mars