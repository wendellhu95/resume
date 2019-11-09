# 胡文召 - 前端工程师

## 基本信息和联系方式

- 👦 胡文召
- 👨‍🎓 中国科学技术大学软件工程硕士在读
- 🕯️ 1995 / 12
- 📮 [wendzhue@gmail.com](mailto:wendzhue@gmail.com)
- 🎤 ng-zorro-antd 主要维护者, @ant-design/icons-angular 作者

## 工作经历

### 2019.11 ~ 今 腾讯微信 前端工程师

### 2018.6 ~ 2019.9 阿里巴巴计算平台事业部 前端实习生

- 参与阿里实时计算开发平台的设计与开发.
- 参与 flink front end 前端项目的 rework.
- Angular 组件库开发.
- 负责代码编辑器与语言服务.

以上仅是梗概, 具体内容请阅读下面的[公司项目部分](#公司项目).

## 教育经历

### 2017 ~ 2020.6 中国科学技术大学 软件工程硕士

### 2013 ~ 2017 对外经济贸易大学 工商管理学士

## 项目

### 公司项目

#### [阿里实时计算开发平台](https://data.aliyun.com/product/sc) (阿里巴巴)

实时计算（原阿里云流计算）是一套基于 Apache Flink 构建的一站式、高性能实时大数据处理平台.

- 日常需求维护.
- 开发盯屏大盘, 展示流作业关键性能参数并提供阈值报警, 全配置使用, 使用户无须了解 Grafana 的 API 也可以使用, 双十一期间被部分团队采用监控流作业运行情况.
- 从文档生成代码片段和关键字提示, 提高网页代码编辑器的使用体验.
- 开发一些内部工具的前端, 例如对比 Blink 不同版本的小工具 Blink Release Guard, 分析 Blink 引擎性能的 profiler 可视化工具 Flame Runner 等.

#### [flink runtime web 重构](https://github.com/apache/flink/tree/master/flink-runtime-web/web-dashboard/src) (阿里巴巴)

使用最新的 Angular 技术重构 Apache Flink 的 runtime 界面, 目前已被采用为默认的界面来替换老版本.

- 负责部分界面的开发.

#### [@ng-zorro/ng-plus](https://www.npmjs.com/package/@ng-zorro/ng-plus)（阿里巴巴）- 原作者

基于 ng-zorro-antd 的内部使用的增强组件库. 用于阿里实时计算开发平台, flink runtime web 和其他多个内部产品.

- 开发了 resize / monaco editor wrapper / flow chart editor 等组件.

#### @ali/ng-zorro-language-service (阿里巴巴) - 原作者

为类 SQL 语言提供格式化, 智能提示, 语法检查等语言服务, 支持阿里实时计算开发平台等产品.

- 编写了分词器, 解析器和格式化器, 并撰写了多个适配器, 使得语言服务能够运行在不同的环境当中.

### 开源项目

#### [ng-zorro-antd](https://github.com/NG-ZORRO/ng-zorro-antd) - 主要维护者

基于 Angular 和 Ant Design 设计规范的 Angular 组件库. 目前在 GitHub 上有 5,000+ star, npm 上每月有 70,000 下载量.

- 负责十余个组件的维护和功能的开发, 开发新的组件等, [可以在这里看到我的工作](https://github.com/NG-ZORRO/ng-zorro-antd/pulls?q=is%3Apr+is%3Aclosed+author%3Awendzhue).
- 开发和撰写 [ng-zorro-antd 新手入门项目](https://github.com/NG-ZORRO/today-ng-steps).
- 使用 Gatsby 搭建了我们的[官方博客](https://ng.ant.design/blog).

#### [@ant-design/icons-angular](https://github.com/ant-design/ant-design-icons/tree/master/packages/icons-angular) - 原作者

Ant Design Icons 的 Angular 适配库, ng-zorro-antd 的依赖. 目前在 npm 上每月有 70,000 下载量.

- 支持图标资源的动态和静态加载, 动态加载请求复用, 自定义图标, 命名空间等功能.
