# eureka
基于springcloud构建eureka服务，提供几种环境变量参数注入，动态调整eureka，用于作为基础jar，引入到docker镜像中，通过docker、k8s和helm。

## 1. 环境变量说明
### 1.1 APP_NAME
APP_NAME：应用名
### 1.2 APP_PORT
APP_PORT：应用端口
### 1.3 EUREKA_HOSTNAME
EUREKA_HOSTNAME: 本地应用hostname，用于区分不同eureka节点
### 1.4 EUREKA_URL_LIST
EUREKA_URL_LIST：统一Eureka集群入口，可以使用Service的k8s域名作为访问入口

