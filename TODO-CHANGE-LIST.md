### 问题：因virtualgl对111以上的chrome不支持，故有个该fork项目，该项目的目的是为了让neko可以支持最新版本的chrome，并且使用nvidia作为gl
### 已调整列表：
- 1、更改neko依赖的基础镜像
- 2、剔除项目内对mesa的依赖
- 3、剔除项目内对virtualgl的依赖
- 4、更改xorg配置，让其支持nvidia
- 5、修改base/supervisor.conf x-server配置，让其支持多显示器



