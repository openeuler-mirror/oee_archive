# oee_archive

#### Description
The code repo is to be stored upstream packages that not include by openeuler

#### Instructions

1.  when we add upstream package, we should comply standards as fold/compress
2.  when we get upstream package, we should modify SRC_URI param in yocto-meta-openeuler's bb or bbappend file, get line that contains compress and alter it to start with file, e.g:
    file://oee_archive/${BPN}/xxx.tar.gz
3.  every time you alter the oee_archive repo, you should modify openEuler Embedded's base line

#### Contribution

1.  Fork the repository
2.  Create Feat_xxx branch
3.  Commit your code
4.  Create Pull Request


#### Gitee Feature

1.  You can use Readme\_XXX.md to support different languages, such as Readme\_en.md, Readme\_zh.md
2.  Gitee blog [blog.gitee.com](https://blog.gitee.com)
3.  Explore open source project [https://gitee.com/explore](https://gitee.com/explore)
4.  The most valuable open source project [GVP](https://gitee.com/gvp)
5.  The manual of Gitee [https://gitee.com/help](https://gitee.com/help)
6.  The most popular members  [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
