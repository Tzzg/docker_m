# docker_m
php docker多版本兼容方案


1 先 git clone
2 cd docker_app/build 下
3 因为暂时没想到 yml 里创建网络的办法，先
  docker network create z-net
  //命名你随意
4 docker-compose up -d拉起整个项目
5 docker stats 查看当前镜像状态
