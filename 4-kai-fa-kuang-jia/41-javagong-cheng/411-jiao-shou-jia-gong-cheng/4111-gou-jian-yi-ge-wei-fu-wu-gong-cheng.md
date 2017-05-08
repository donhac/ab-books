### 4.1.1.1 通过脚手架生成基础工程

微服务开发套件提供了快速开发脚手架，一键生成基础工程骨架，它囊括了简单易用且功能强大的开发框架。

**通过以下命令配置生成基础工程**

```
mvn archetype:generate                                      \
  -DarchetypeGroupId=io.appbricks                           \
  -DarchetypeArtifactId=appbricks-archetype-dubbox-service  \
  -DarchetypeVersion=3.0                                    \
  -DgroupId=com.foreveross                                  \
  -DartifactId=sample                                       \
  -DarchetypeCatalog=local
```

### 4.1.1.2 基础工程目录结构

生成工程目录结构如下：

```
.
└── sample
    ├── pom.xml
    ├── public
    │   └── index.html
    └── src
        ├── main
        │   ├── java
        │   │   └── com
        │   │       └── foreveross
        │   │           ├── Application.java
        │   │           ├── config
        │   │           │   └── package-info.java
        │   │           ├── domain
        │   │           │   └── Product.java
        │   │           ├── repository
        │   │           │   └── ProductRepository.java
        │   │           └── service
        │   │               ├── extension
        │   │               │   ├── ApiExceptionMapper.java
        │   │               │   ├── ClientTraceFilter.java
        │   │               │   ├── CustomExceptionMapper.java
        │   │               │   ├── DynamicTraceBinding.java
        │   │               │   ├── DynamicTraceInterceptor.java
        │   │               │   ├── TraceFilter.java
        │   │               │   └── TraceInterceptor.java
        │   │               ├── optimizers
        │   │               │   └── SerializationOptimizerImpl.java
        │   │               ├── rest
        │   │               │   ├── ProductRestServiceImpl.java
        │   │               │   └── api
        │   │               │       └── ProductRestService.java
        │   │               └── rpc
        │   │                   ├── api
        │   │                   │   └── package-info.java
        │   │                   └── package-info.java
        │   └── resources
        │       ├── application-dev.properties
        │       ├── application-prod.properties
        │       ├── application.properties
        │       ├── dubbo-prod.properties
        │       ├── dubbo.properties
        │       ├── logback-dev.xml
        │       ├── logback-prod.xml
        │       └── spring
        │           └── services.xml
        └── test
            ├── java
            │   └── com
            │       └── foreveross
            └── resources
```



