## 2. 基础设施


<table>
   <tr>
      <td>类型</td>
      <td>项目名称</td>
      <td>简介</td>
      <td>代码仓库</td>
   </tr>
   <tr>
      <td rowspan=4>数据库</td>
      <td>ab-oracle</td>
      <td>docker部署oracle 11g</td>
      <td><a href="http://git.oschina.net/gdesign/ab-oracle">http://git.oschina.net/gdesign/ab-oracle</a></td>
   </tr>
   <tr>
      <td>ab-mysql</td>
      <td>docker部署mysql</td>
      <td><a href="http://git.oschina.net/gdesign/ab-mysql">http://git.oschina.net/gdesign/ab-mysql</a></td>
   </tr>
   <tr>
      <td>ab-mongo</td>
      <td>开箱即用的mongodb镜像构建</td>
      <td><a href="http://git.oschina.net/gdesign/ab-mongo">http://git.oschina.net/gdesign/ab-mongo</a></td>
   </tr>
   <tr>
      <td>ab-DataX</td>
      <td>数据库定时备份与恢复</td>
      <td><a href="http://git.oschina.net/gdesign/ab-DataX">http://git.oschina.net/gdesign/ab-DataX</a></td>
   </tr>
   <tr>
      <td rowspan=2>注册中心</td>
      <td>ab-zookeeper</td>
      <td>微服务注册中心，支持集群模式</td>
      <td><a href="http://git.oschina.net/gdesign/ab-zookeeper">http://git.oschina.net/gdesign/ab-zookeeper</a></td>
   </tr>
   <tr>
      <td>ab-zkzupapa</td>
      <td>按规则在zokeeper上建立结构</td>
      <td><a href="http://git.oschina.net/gdesign/ab-zkzupapa">http://git.oschina.net/gdesign/ab-zkzupapa</a></td>
   </tr>
   <tr>
      <td>负载均衡器</td>
      <td>ab-traefik</td>
      <td>Traefik是一个新型的http反向代理、负载均衡软件，能轻易的部署微服务. 它支持多种后端 ,可以对配置进行自动化、动态的管理</td>
      <td><a href="http://git.oschina.net/gdesign/ab-traefik">http://git.oschina.net/gdesign/ab-traefik</a></td>
   </tr>
   <tr>
      <td>分布式缓存</td>
      <td>ab-redis</td>
      <td>docker搭建redis集群</td>
      <td><a href="http://git.oschina.net/gdesign/ab-redis">http://git.oschina.net/gdesign/ab-redis</a></td>
   </tr>
   <tr>
      <td rowspan=2>分布式消息队列</td>
      <td>ab-rabbitmq-demo</td>
      <td>采用rabbitMq消息队列服务,演示消息的异步处理。以及如何启动、关闭微服务</td>
      <td><a href="http://git.oschina.net/gdesign/ab-rabbitmq">http://git.oschina.net/gdesign/ab-rabbitmq</a></td>
   </tr>
   <tr>
      <td>ab-rabbitmq</td>
      <td>基于 rabbitmq 的 docker镜像化集群方案</td>
      <td><a href="http://git.oschina.net/gdesign/gd-mq">http://git.oschina.net/gdesign/gd-mq</a></td>
   </tr>
   <tr>
      <td rowspan=2>微服务健康检测</td>
      <td>ab-healthcheck</td>
      <td>对接上kong服务，支持微服务的健康检查</td>
      <td><a href="http://git.oschina.net/gdesign/ab-healthcheck">http://git.oschina.net/gdesign/ab-healthcheck</a></td>
   </tr>
   <tr>
      <td>ab-doctor</td>
      <td>对接zookeeper与traefik的微服务健康检测</td>
      <td><a href="http://git.oschina.net/gdesign/ab-doctor">http://git.oschina.net/gdesign/ab-doctor</a></td>
   </tr>
   <tr>
      <td>API网关</td>
      <td>ab-gateway</td>
      <td>采用kong实现对微服务api的统一管理</td>
      <td><a href="http://git.oschina.net/gdesign/ab-gateway">http://git.oschina.net/gdesign/ab-gateway</a></td>
   </tr>
   <tr>
      <td>日志系统</td>
      <td>ab-efk</td>
      <td>基于Elasticsearch+Fluentd+Kibana的日志收集分析系统</td>
      <td><a href="http://git.oschina.net/gdesign/ab-efk">http://git.oschina.net/gdesign/ab-efk</a></td>
   </tr>
   <tr>
      <td>Docker可视化管理</td>
      <td>ab-shipyard</td>
      <td>集成管理docker容器、镜像、Registries，支持多节点的集成管理，可以动态加载节点，可托管Node(服务器)的容器</td>
      <td><a href="http://git.oschina.net/gdesign/ab-shipyard">http://git.oschina.net/gdesign/ab-shipyard</a></td>
   </tr>
   <tr>
      <td rowspan=3>持续集成部署</td>
      <td>ab-jenkins</td>
      <td>基于jenkins的持续集成环境</td>
      <td><a href="http://git.oschina.net/gdesign/ab-jenkins">http://git.oschina.net/gdesign/ab-jenkins</a></td>
   </tr>
   <tr>
      <td>ab-cicd</td>
      <td>python版简易持续集成</td>
      <td><a href="http://git.oschina.net/gdesign/ab-cicd">http://git.oschina.net/gdesign/ab-cicd</a></td>
   </tr>
   <tr>
      <td>ab-cicdv2</td>
      <td>基于git-webhook的自动化部署和运维系统</td>
      <td><a href="http://git.oschina.net/gdesign/ab-cicdv2">http://git.oschina.net/gdesign/ab-cicdv2</a></td>
   </tr>
   <tr>
      <td rowspan=2>自动化运维</td>
      <td>ab-ansible</td>
      <td>ansible是新出现的运维工具是基于Python研发的糅合了众多老牌运维工具的优点实现了批量操作系统配置、批量程序的部署、批量运行命令等功能</td>
      <td><a href="http://git.oschina.net/gdesign/ab-ansible">http://git.oschina.net/gdesign/ab-ansible</a></td>
   </tr>
   <tr>
      <td>ab-admin</td>
      <td>dubbo的管理控制台运维，该管理控制台为内部裁剪版本，开源部分主要包含：路由规则，动态配置，服务降级，访问控制，权重调整，负载均衡，等管理功能</td>
      <td><a href="http://git.oschina.net/gdesign/ab-admin">http://git.oschina.net/gdesign/ab-admin</a></td>
   </tr>
   <tr>
      <td rowspan=2>系统监控</td>
         </tr>
   <tr>
      <td>ab-monitor</td>
      <td>dubbo服务的监控系统,以图表的形式展示dubbo注册接口调用情况(次数，延迟等)，可以查看所有注册的服务</td>
      <td><a href="http://git.oschina.net/gdesign/ab-monitor">http://git.oschina.net/gdesign/ab-monitor</a></td>
   </tr>
   <tr>
      <td>mock服务</td>
      <td>ab-mock</td>
      <td>基于数据模板生成数据,使前端可独立于后端开发与测试</td>
      <td><a href="http://git.oschina.net/gdesign/ab-mock">http://git.oschina.net/gdesign/ab-mock</a></td>
   </tr>
   <tr>
      <td>服务调用跟踪</td>
      <td>ab-hydra</td>
      <td>基于Dubbo的调用跟踪系统,可以接入各种基础组件，完成对业务系统的跟踪</td>
      <td><a href="http://git.oschina.net/gdesign/ab-hydra">http://git.oschina.net/gdesign/ab-hydra</a></td>
   </tr>
   <tr>
      <td>docker私有仓库</td>
      <td>ab-harbor</td>
      <td>Harbor项目是帮助用户迅速搭建一个企业级的registry 服务，包括了权限管理(RBAC)、LDAP、审计、管理界面、自我注册、HA等企业必需的功能，同时针对中国用户的特点，设计镜像复制和中文支持等功能</td>
      <td><a href="http://git.oschina.net/gdesign/ab-harbor">http://git.oschina.net/gdesign/ab-harbor</a></td>
   </tr>
</table>