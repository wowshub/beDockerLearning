#### 1 docker基础
#### 时间：20241013

dockerfile 从基础镜像建立自己的docker镜像
docker镜像 如游戏光盘
docker容器 如游戏光盘中的各个游戏
docker层 如光盘中一圈一圈的从 小到大 从内到外 小/内圈 为基础层 
        大/外圈为每个，支持软件 游戏软件 每个层都可以被共享和利用
        减少内存的使用和效率

dockerfile 先建立镜像文件 从上到下的命令行 如 beDockerApp
docker build . 在.根目录下建立一个镜像 成功后出现一个镜像的ID
docker tag 镜像ID 为镜像自定义一个好记的名称

docker run -i -t -p 8000:8000 --name 容器名 镜像名


