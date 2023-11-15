# oee_archive

#### 介绍
该仓承担openEuler Embedded中未被openEuler收录的源码包存放地址

#### 使用说明

1.  录入时存放目录结构为包名/压缩包
2.  获取时在yocto-meta-openeuler源码的bb文件或bbappend文件中修改SRC_URI变量，对于压缩包相关的设定以file字段开头，参考以下范例：
    file://oee_archive/${BPN}/xxx.tar.gz
3.  每一次的该仓修改需要同步修改openEuler Embedded的基线文件

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
