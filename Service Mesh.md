# 什么是Service Mesh  服务网格

蚂蚁金福 mson ,轻舟

第一代：Cloud ,Dubbo           nginx 做keliveper

第二代：微服务

> 架构师 ：微服务考虑的点：
>
> 	1. 服务注册于发现
>  	2. 负载均衡

<font color="red">三种服务模式：</font>

1. 集中式代理：负载均衡，nginx,   ip :port --> nginx  ---> 服务
2. 嵌入式代理： eureka-client. client, （naconsdiscoremy.jar,eurekaclient.jar  语言绑定。基础架构组，二方库）
3. 主机独立进行代理。沉淀到底层，进程中，和原来的服务进程**脱钩**；

istio 是serice mesh 一种实现:

问什么作用？

1. 减轻开发的工作量（docker,K8s）
2. 云原生 Cloud native, 微服务： devops、持续交付、容器化

istio

docker k8s books

istio

kiali 监控

istio

注入

注入的原理

注入后 Containe

<font color="red">二进制安全：他只去字节流，只要有统一的编解码，数据就不会被破坏。</font>