# Skills

通用 Agent Skills 集合，不绑定特定项目，开箱即用。

## 安装

```shell
npx skills add javahongxi/skills
```

## 可用 Skills

| Skill                                                            | 说明                                                                       | 触发方式                           |
|------------------------------------------------------------------|--------------------------------------------------------------------------|--------------------------------|
| [hongxi-alibaba-java-review](skills/hongxi-alibaba-java-review/) | 基于《阿里巴巴Java开发手册》的代码审查，覆盖 8 大维度，兼容 Java 17+                               | "审查代码是否符合阿里规范" / "code review" |
| [hongxi-tech-blog-writer](skills/hongxi-tech-blog-writer/)       | 基于 javahongxi 博文风格的技术博客写作助手，支持项目推广、技术深度解读、全景介绍、升级公告 4 种模板                | "帮我写篇推广博文" / "写一篇技术博客"         |
| [hongxi-java-dev-env-setup](skills/hongxi-java-dev-env-setup/)   | 在新 Mac 上一键搭建 Java 全栈开发环境（JDK 17/21、Maven、Redis、ZooKeeper、Nacos、MySQL、Go） | "搭建 Java 开发环境" / "初始化开发机"      |

## 使用

安装后，在 Qoder 中直接对话触发：

```
# 审查单个文件
帮我审查 UserService.java 是否符合阿里规范

# 审查 git diff
检查我这次提交的代码有没有违反阿里规范

# 只检查某个维度
检查这段代码的并发处理是否符合阿里规范

# 写一篇推广博文
帮我写一篇推广博文介绍这个项目

# 写一篇技术深度解读
帮我写一篇 Spring AI 模块的深度解读

# 搭建 Java 开发环境
帮我在 Mac 上初始化 Java 开发环境

# 配置开发机
新 Mac 需要搭建开发环境，安装 Java、Redis、MySQL、Nacos 等
```

&copy; [hongxi.org](http://hongxi.org)
