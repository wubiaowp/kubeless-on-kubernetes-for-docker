
    前言：Kubeless环境已经集成、通过UI来管理创建Function执行任务
  
    1、链接: https://pan.baidu.com/s/10dv-zQPKM1eXpM87w3ONNQ  密码: uemp
    
      【如果从官网直接下载版本兼容问题需要修改deployment】
    
    2、kubectl create -f k8s.yaml 
    
    3、查看Pods是否创建完成：kubectl get pods -n kubeless
    
    4、查看Pods对外端口：kubectl get svc -n kubeless
       
    5、浏览器输入：http://localhost:31880