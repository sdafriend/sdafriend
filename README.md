# bubble-UI 组件库

#### 介绍
bubble-UI组件库的环境搭建：
  技术选型： vue3 + typescript + babel + sass + vite;
  代码提交:    husky统一git提交检验;
  代码风格:    eslint + prettier;
  文档开发:    vitepress;

#### 软件架构
软件架构说明

版本说明： 
    pnpm版本  7.25.0
    node版本  16.18.0

#### 环境运行教程
打开终端，输入以下命令:
1.  pnpm install
2.  pnpm run dev

#### 项目目录解析
    example： 用于调试预览（对比Elment-plus的是paly）
        index.html: html文件启动
        main.ts: 入口文件 (ts项目,引入vue组件需要typings配置)
        app.vue: 基础vue项目的搭建
        package.json: 模块描述文件，包含基本的设置及结果
        vite.config.ts: 配置Vite
    typings: 对于main.ts中申明类型但未申明进行配置
        vue-shim.d.ts: 具体配置
    packages：基本大部分的开源项目的组件库代码都是放在其中
        components放置组件
        theme-chalk放置样式文件
        utils放置公共文件
    .npmrc: 对pnpm进行一些简单的配置
    package.json: 模块描述文件，包含基本的设置及结果
    pnpm-workspace.yaml： Monorepo结构需要依赖的一个配置文件
    tsconfig.json: ts的基础配置文件

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)