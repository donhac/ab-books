###4.1.1.1 构建一个微服务
#####(1) 通过脚手架生成基础工程
微服务开发套件提供了快速开发脚手架，一键生成基础工程骨架，它囊括了简单易用且功能强大的开发框架。

**通过以下命令配置生成基础工程：**

```
mvn archetype:generate                                      \
  -DarchetypeGroupId=io.appbricks                           \
  -DarchetypeArtifactId=appbricks-archetype-dubbox-service  \
  -DarchetypeVersion=3.0                                    \
  -DgroupId=com.foreveross                                  \
  -DartifactId=sample                                       \
  -DarchetypeCatalog=local
```

**生成的目录结构**