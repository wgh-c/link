#

## framework

1. [react](https://react.docschina.org)

2. [vue](https://cn.vuejs.org/)

## css

1. [css to unocss](https://to-unocss.netlify.app)

2. [tailwindcss](https://tailwind.nodejs.cn/docs/installation)

## Three.js

1. [《探索 three.js》](https://discoverthreejs.com/zh/)

2. [Manual](https://threejs.org/manual/)

## UI

1. [PhotoShop](./photoshop)

## 服务器

1. [mysql 安装](https://blog.csdn.net/m0_74824661/article/details/143985660)
2. redis
   - [redis 下载](https://github.com/redis/redis/releases/tag/6.2.6)
   - [redis 配置](https://blog.csdn.net/weixin_50083085/article/details/136881160)
3. [jdk](https://blog.csdn.net/weixin_41394654/article/details/123442460)
4. [部署](https://blog.csdn.net/Elon15/article/details/124516929)
5. [nginx](https://blog.csdn.net/whatareyouding/article/details/144317654)
6. [node](https://blog.csdn.net/qq_37955704/article/details/113395046)
7. docker
   启动命令

   ```shell
   docker run -d -p 8080:8080 -p 50000:50000 --name jenkins -v /usr/local/jenkins-container-config:/var/jenkins_home --restart unless-stopped -e JENKINS_URL=http://8.156.65.210/jenkins/ -e JENKINS_OPTS="--prefix=/jenkins"  jenkins/jenkins:lts-jdk17
   ```

   1. `-v /usr/local/jenkins-container-config:/var/jenkins_home` 使用本地目录 Jenkins 的配置和数据
   2. `--restart unless-stopped` unless-stopped: 容器停止时重启，除非被手动停止
   3. `-e JENKINS_URL=http://8.156.65.210/jenkins/` 通过环境变量来设置 Jenkins 基本 URL
   4. `-e JENKINS_OPTS="--prefix=/jenkins"` 设置子路径
