## 工作简介:
三年大数据开发(Scala/Spark/Golang)经验, 五年运维经验, 目前主要做高并发日志流处理相关项目, 同时负责监控和自动化运维(Prometheus/Grafana/Puppet/Salt/Ansible)的部署和开发, 以及配置中心(Golang/Etcd/Vuejs)和集群前端应用网关(Resty/Lua)等基础组件的设计和开发. 鉴于开发&运维双经验, 在设计项目和基础组件时能很好的结合双方视野综合考虑问题, 也能更好的和项目等非技术团队沟通客户需求. 希望下一个团队没有过多职位界限, 进而能更好的发挥个人优势.

## 基本资料:
- 性别: 男
- 出生年份: 1989
- 工作经验: 8年以上 (技术相关)
- GitHub: whisperaven

## 求职意向:
- 大数据开发 (目前主要语言为Scala) / Linux运维 (最好偏向大数据或容器方向)

## 工作和项目经历:
##### 2017.10-Today | CDN 日志大数据团队 | Scala 大数据开发 / 大数据运维
- 独立设计和开发Scala/Akka事件处理引擎(经典的Sorce/Sink模式): http://github.com/whisperaven/atiesh;
- 基于上述引擎开发日志流业务, 消费Kafka进行数据处理, 最终将数据通过各种协议转发给客户, 峰值QPS100万;
- 基于上述引擎开发日志收集Agent, 读取文件并通过Https上传中央, 目前部署万台级别服务器并资源占用友好;
- 基于上述引擎开发日志接收Server, 接收自研Agent和合作方日志传输, 并写入Kafka集群, 峰值QPS100万;
- 独立完成基于Ansible/Prometheus/Grafana的运维工具链, 为上述业务实现监控/自动化/代码发布方案;
- 独立完成NginxLua网关配合Etcd做服务发现和动态配置管理, 配合双向Https为上述业务实现内&外部访问;
- 使用stap捕获VFS写调用排错系统奇怪的IO峰值, 捕获并跟踪特定线程的调用排查奇怪的线程卡顿问题;
- 根据业务特点调整JVM参数优化小应用内存占用, 以及分析GC日志调整各生代大小和比例降低GC延迟;

##### 2016.08-2017.06 | CDN 运维团队 | Linux运维工程师
- 独立完成CDN业务线缓存业务的部署标准化设计和.deb打包和APT源等相关基础设施建设工作;
- 独立完成监控报警系统(Zabbix)的设计和构建, 以及所有取值脚本和监控自动化维护工具的开发; 
- 独立完成基于Ansible的自动化工具链, 并独立开发异步模块化的Ansibe Restful API(Celery/Cherrypy);
- 独立完成业务平滑发布工具(检测更改Upstream)的开发, 并以模块的方式动态加载至自己写的Ansible API;
- 独立完成基于Redis/Golang开发简单资产接口, 并配合Ansibe动态资产功能整合Ansible;
- 独立基于Vuejs开发单页前端App, 并整合上述自己开发的资产接口和Ansible接口实现UI化运维平台;
- 自主开发的模块化Ansible Restful API代码及文档: http://github.com/whisperaven/0ops.exed;

##### 2015.07-2016.07 | 视频网站运维团队 | Linux运维工程师
- 独立完成自动化工具(SaltStack)的设计和实现, 并通过Salt Python API进行功能扩展;
- 独立完成存储系统的搭建和维护(GlusterFS)以及提供增删改查的RestFul存储接口的开发(Golang);
- 负责全站前端Nginx的维护和线上业务运维, 以及基于Nginx/Lua实现的鉴权等请求过滤功能;
- 独立完成测试环境的设计和维护, 基于Salt+Jenkins+KVM实现的高效(10分钟内部署一整套业务)虚拟化环境;
- 独立完成Pxe/Yum/Bind等基础组件的设计和建设, 实现15分钟从裸机到上线的高效部署;

##### 2013.07-2014.04 | CDN 运维团队 | Linux运维工程师
- 独立完成监控报警系统(Zabbix/130k items/5k triggers/500+ nvp)的设计和构建, 以及取值脚本和监控自动化维护工具的开发; 
- 独立完成自动化工具(Puppet/2 Master with NginxPassenger)的设计和构建, 以及业务部署代码(puppet manifest)的编写;
- 负责新技术的调研和应用, 包括: FlashCacheSSD优化IO吞吐量/Ceph集群存储方案等;
- 负责所有运维工具的开发, 多数基于CLI, 包括监控信息同步(通过调用ZabbixApi和资产库), CDN访问和流量报告生成等(Regex/Awk);

##### 2011.05-2013.05 | 视频网站运维团队 | Linux运维工程师
- 独立完成监控报警系统(Cacti/Nagios)的设计和构建, 以及相关工具(e.g.: 简单的流量分析脚本)的编写.
- 负责类CDN结构视频播放集群的搭建和维护, 存储层和缓存层以及负载均衡分别由GlusterFS/Nginx/NginxUpstream实现.
- 负责运维工具的开发, 包括多线程数据迁移, 日志分析等脚本, NginxFLV模块的简单修改.

##### 2008.07-2011.05 | IT 外包&外派 | Linux/Mac/Windows技术支持工程师
- 公司主要为中小型企业提供IT支持和Linux项目的实现和维护, 同时还为大型企业提供外派工程师;
- 前期主要负责公司为客户提供的基于ExtMail的邮件系统维护及Samba等Linux下应用的搭建;
- 后期被外派常驻瞬联科技, 设计实现了多个基于LAMP的Web应用(Wiki/CMS/Bug追踪/资产管理等)以及LDAP目录服务;
