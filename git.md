# 1.版本控制

![image-20231230094903920](E:\学习笔记\git\images\git.assets\image-20231230094903920.png)

## 1.本地版本控制

## 2.集中式版本控制

![image-20231230095410586](E:\学习笔记\git\images\git.assets\image-20231230095410586.png)



## 3.分布式版本控制

![image-20231230095610821](E:\学习笔记\git\images\git.assets\image-20231230095610821.png)







![image-20231230095729830](E:\学习笔记\git\images\git.assets\image-20231230095729830.png)



# 2.GIT安装

1.删除

* 查看环境变量，删除
* 打开控制面板卸载git



2.安装 下一步

# 3.GIT配置

```shell
git config -l    #git 所有的配置
```

![image-20231230103457761](E:\学习笔记\git\images\git.assets\image-20231230103457761.png)



```shell
git config --system --list #系统配置
```

![image-20231230103723553](E:\学习笔记\git\images\git.assets\image-20231230103723553.png)

```shell
git config --global --list  #用户配置
```

![image-20231230103904010](E:\学习笔记\git\images\git.assets\image-20231230103904010.png)



**GIT相关配置文件**

1) GIT\etc\gitconfig          --system

![image-20240102182832719](E:\学习笔记\git\images\git.assets\image-20240102182832719.png)

1)C:user\Administrato\\. gitconfig         当前用户的

![image-20240102182733744](E:\学习笔记\git\images\git.assets\image-20240102182733744.png)

![image-20240102182746862](E:\学习笔记\git\images\git.assets\image-20240102182746862.png)



> 设置用户名与邮箱

```shell
git config --global user.name "hnsqls"
git config --global user.emial "2661108038@qq.com"
```





# 4. GIT理论

> 工作区域

GIT有四个工作区域，工作区（Working Directory），缓存区（Stage/index），本地仓库（GIt Directory），远程仓库（Remote Directory）

![image-20240102184122233](E:\学习笔记\git\images\git.assets\image-20240102184122233.png)

![image-20240102184850614](E:\学习笔记\git\images\git.assets\image-20240102184850614.png)



> 工作流程

![image-20240102185256766](E:\学习笔记\git\images\git.assets\image-20240102185256766.png)



# 5.GIT项目搭建

> 创建工作目录与常用指令

![image-20240102185455111](E:\学习笔记\git\images\git.assets\image-20240102185455111.png)





> 本地搭建仓库

选择合适位置进入git bsah，执行初始化指令，会在该位置生成 .git文件

```shell
git init    #创建全新的仓库
```



> 克隆远程仓库

* 就是将远程的仓库复制到本地

```shell
git clone [url]
```



# 6.GIT 文件状态

![image-20240102191742161](E:\学习笔记\git\images\git.assets\image-20240102191742161.png)

![image-20240102193306323](E:\学习笔记\git\images\git.assets\image-20240102193306323.png)

![image-20240102194258664](E:\学习笔记\git\images\git.assets\image-20240102194258664.png)





# 7.GIT使用

密钥 : 在 c：/administar/.ssh 打开git bash

```bash
ssh-keygen -t rsa
```



![image-20240102200345345](E:\学习笔记\git\images\git.assets\image-20240102200345345.png)







# 8. IDEA集成、GIT

