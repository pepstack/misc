# misc
杂项合集

## Windows 上 java 开发环境变量配置:

DEVPACK_HOME=c:\DEVPACK
CYGWIN_HOME=%DEVPACK_HOME%\cygwin64
ANT_HOME=%DEVPACK_HOME%\apache-ant-1.9.6
JAVA_HOME=%DEVPACK_HOME%\java\jdk1.8.0_162
JRE_HOME=%DEVPACK_HOME%\java\jre1.8.0_162
MAVEN_HOME=%DEVPACK_HOME%\apache-maven-3.3.3
MAVEN_OPTS=-Xms256m -Xmx512m -Dfile.encoding=UTF-8
CLASSPATH=.;%JAVA_HOME%/lib/tools.jar;%JAVA_HOME%/lib/dt.jar

Path=.........;%JAVA_HOME%\bin;%JRE_HOME%\jre1.8.0_162\bin;%ANT_HOME%\bin;%MAVEN_HOME%\bin
