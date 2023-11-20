# zeebe-kafka-exporter

## 构建注意事项
+ 确保环境变量JAVA_HOME为jdk11或者以上


然后执行
```
 mvn clean install -DskipTests  -Dcheckstyle.skip=true
```

即可得到
```
exporter/target/zeebe-kafka-exporter-3.1.2-SNAPSHOT-jar-with-dependencies.jar
```

