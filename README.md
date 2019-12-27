# Myblog
使用Springboot搭建个人博客


# 前言

一直想搭建自己的博客,之前使用过hexo+github搭建自己的博客,但是每次都需要线下编辑完md之后,再编译,发布到github上. 太繁琐,就放下了.

后来使用WordPress搭建自己的博客,奈何WordPress配置,调试的时间太久,都无法达到自己的预期效果.

后来寻思,自己搞技术的,还是自己搭建吧,前后台都自己做,无论好与不好,最少,自己会受益匪浅.



# 构思:

核心功能点:
1. 基本架构: 前后台分离,有了后台数据,前台模板到时候可以进行替换.

2. 文章管理.
  - 在线编辑文章. 目前考虑,仅使用markdown之内的语法. 
  - 文章管理. 增删查改
  - 文章分类 [tag和分类]
  - 评论管理

1.需要能够在线编译,目前图床优先使用阿里云吧.麻烦一点无所谓




# 项目搭建:

springboot / Spring 来搭建后台.

MyBaties 实现ORM的持久.

Restful/JSON 实现前后台数据交互

bootstrap 来构建交互界面.



# 参考:

[SpringBoot技术栈搭建个人博客【项目准备】](https://www.jianshu.com/p/0293368fe750)


[SpringBoot技术栈搭建个人博客【后台开发】](https://www.jianshu.com/p/91c6c9fc67c4)

[SpringBoot技术栈搭建个人博客【前台开发/项目总结】](https://www.jianshu.com/p/c66541e59249)
