
      
      版本环境：MacOS10.15.7、Docker2.2.2、Kubernetes1.16.5、Kubeless1.0.7
      
      Docker与Kubernetes集成请参考：https://github.com/wubiaowp/kubernetes-for-docker-desktop-mac
   
   一、Kubeless下载地址（MacOS版本）
  
      链接: https://pan.baidu.com/s/19tSw0Taez91gjdZFIXUWJQ  密码: 5d1a
    
    
   二、解压完切换到当前文件夹下、配置Kubeless环境变量
   
      sudo mv bundles/kubeless_darwin-amd64/kubeless /usr/local/bin
      
   三、查看安装是否成功
      
      kubeless version
       
      kubeless function ls
      
   四、基于Kubernetes创建Kubeless空间
   
      kubectl create ns kubeless
      
      kubectl get pods -n kubeless
      
   五、创建Controller、Manager（下载yaml文件）
   
     链接: https://pan.baidu.com/s/1dtwiv71fBftscmAIq5jE9A  密码: 74fq
     
     kubectl create -f kubeless-non-rbac-v1.0.7.yaml
     
   六、查看创建是否成功
   
     kubectl get pods -n kubeless
     
     kubectl get deployments -n kubeless
     
     kubectl get customresoucedefinition
     
   七、详情请参考
   
     https://my.oschina.net/wubiaowpBlogShare/blog/4263517
     
    
    
               