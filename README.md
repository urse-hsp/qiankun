# 微应用的名称 package.json => name 需要和主应用中注册时的 name 相对应，且必须确保唯一。

<!-- qiankuun  -->

# React react-scripts@5.0.1运行错误 导致项目无法启动 安装的react-scripts@4.0.3 版本

# Vue vue-router@4.x 运行错误，导致项目无法启动 安装的@3.5.2 版本

# 子应用注册

{
name: 'reactjs', // 对应子应用 package > name
entry: 'http://localhost:8011/', // 子应用地址
container: '#subContainer', // 主应用模板 id
activeRule: '/react1', // 应用注册对应 主应用的路由
loader,
},

主应用路由 path 需要跟 qiankun 中注册的 name,activeRule 三者需要一致

# master-umi3 qiankun 插件形式实现

# master-umi4-pro umi 内部 qiankun 插件实现

1、子应用 umi 下载插件后，一键可开启配置
2、umi 开启微前端 qiankun.master 注册子应用。qiankun.slave 开启微服务，需要配置 package.name
3、umi 路由配置中添加 microApp 属性

给子应用传递数据
1 url： 子应用获取 url 后的参数
2 本地缓存: 父子应用，子应用的本地缓存使用的是主应用的。嵌套级应用缓存都是主应用的。
3 父子应用通讯


umi主应用，umi子应用MicroApp可以指定模块显示子应用内容
不需要统一子应用里package.name名字