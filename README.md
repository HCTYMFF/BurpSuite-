# BurpSuite汉化包支持 BurpSuite 1.7* 和 2.*
汉化时需要 jdk 1.8以上的版本
将此文件BurpSuiteCn.jar放在Burp的根目录下，然后cmd执行命令即可
汉化命令:
Linux/Mac:java -javaagent:BurpSuiteCn.jar -Xbootclasspath/p:burp-loader-keygen.jar  -Xmx1024m -jar burpsuite_pro_vx.x.x.jar
Win:java -Dfile.encoding=utf-8 -javaagent:BurpSuiteCn.jar -Xbootclasspath/p:burp-loader-keygen.jar  -Xmx1024m -jar burpsuite_pro_vx.x.x.jar
