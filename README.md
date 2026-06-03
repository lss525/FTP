# FTP   
## 项目结构：  
       FTP/
      ├── fuwuqi.c        //服务器
      ├── client.c        //客户端
      ├── welcome.txt     //测试样本 
      └── README.md       //项目介绍  
          
## 流程步骤：   
### 前置条件：
1.运行服务器代码：  
  - 当出现以下情况，说明服务器开启成功：    

        duankou:2100
        /tmp/ftp_root
  - 当出现运行结束，说明服务器已经开启；  

2.运行客户端代码：  
  - 当出现以下界面时证明连接服务器成功：  
      
        already link 127.0.0.1:2100
        accept:220 welcome to use ftp
         FTP 
        user ->
        pasv  
        ls  
        get
        put 
        cd  
        pwd 
        quit 

        ftp>   
            
   - 当出现以下界面时证明服务器没有开启或者连接未成功：    

          connect failed: Connection refused  
  