#### 1. 你可以按如下命令来生成 sshkey: 

     ssh-keygen -t rsa -C "xxxxx@xxxxx.com"  
     
     # Generating public/private rsa key pair...
     # 三次回车即可生成 ssh key

#### 2. 查看你的 public key，并把他添加到Github（https://github.com） SSH key添加地址: https://github.com/settings/keys)

    cat ~/.ssh/id_rsa.pub
    
    # ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQC6eNtGpNGwstc....

#### 3. 添加后，在终端（Terminal）中输入

    ssh -T xxxxx@xxxxx.com
        
若返回

    Welcome to Gitee.com, yourname!

则证明添加成功。
