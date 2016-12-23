# mybatis-dalgen
自动生成mybatis配置文件及DAO部分代码

##使用方法
1、将本项目拷贝至工程根目录下
2、修改工程相关配置：system-config.properties
3、运行gen.bat文件

##注意

  1、本工程依赖ibatis-dalgen工程的jar包：ibatis-dalgen-1.0.0.jar，需要本地进行maven打包，mvn clean install -Dmaven.test.skip=true
	<dependency>
		<groupId>com.ibatis.dalgen</groupId>
		<artifactId>ibatis-dalgen</artifactId>
		<version>1.0.0</version>
	</dependency>
  2、本工程项目生成结构依赖于domaindemo项目结构
  
