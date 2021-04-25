项目简建立顺序：  
1.leyou-registry  
2.leyou-gateway  
3.leyou-item  leyou-item-interface leyou-item-service  
这里可以顺序启动leyou-registry，leyou-gateway，leyou-item-service  
测试各项目：   
eureka访问地址：http://127.0.0.1:10086  
leyou-item-service:  
通过路由访问：http://127.0.0.1:10010/api/item/actuator/info  
通过真实地址访问：http://127.0.0.1:8081/actuator/info  



