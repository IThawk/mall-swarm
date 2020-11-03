## 启动流程
### 1：启动nacos ：docker restart nacos
### 2：启动redis ：docker restart redis

### 3：启动网关：
    直接运行：com.macro.mall.MallGatewayApplication
### 4： 启动认证服务：
    直接运行：com.macro.mall.auth.MallAuthApplication
### 5：启动 rabbitmq
    docker restart rabbitmq      
### 6：启动后台管理服务mall-admin
    直接运行：com.macro.mall.MallAdminApplication 
### 7：启动前台服务mall-portal     