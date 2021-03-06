# 什么是DataV数据可视化 {#concept_rbr_xjj_p2b .concept}

相比于传统图表与数据仪表盘，如今的数据可视化致力于用更生动、友好的形式，即时呈现隐藏在瞬息万变且庞杂数据背后的业务洞察。无论在零售、物流、电力、水利、环保、还是交通领域，通过交互式实时数据可视化视屏墙来帮助业务人员发现、诊断业务问题，越来越成为大数据解决方案中不可或缺的一环。

创造一个可视化应用，您可能会面临如下的问题：

-   对于数据可视化的设计无从下手，团队内的设计师对于复杂数据的展现经验不足。
-   对于数据可视化的实现比较困难，设计出来的很多图表与特效开发耗时耗力。
-   对于非传统报表数据类型（如时空数据、关系数据）的分析展现，缺乏相关的组件或工具支持。
-   对于在大屏幕上的展示，总会遇到分辨率适配的种种问题。
-   对于大数据的分析展示，现有工具无法很好支撑。

DataV 可以让更多的人看到数据可视化的魅力，并帮助非专业的工程师通过图形化的界面轻松搭建具有专业水准的可视化应用。DataV 提供了丰富的可视化模板，极大程度满足您会议展览、业务监控、风险预警、地理信息分析等多种业务的展示需求。

## 版本规格说明 {#section_ucc_3kj_p2b .section}

DataV 提供了以下四种版本供您选择：

-   **基础版**
    -   发布方式：公开发布。
    -   数据源种类：支持 RDS for MySQL、Analytic DB、CSV、API等七种数据源。
    -   组件和模板种类：提供五个基础模板，支持常规图表和基础地图组件。
    -   项目数量：支持创建 5 个大屏项目，不能扩屏。
    -   其它说明：无。
-   **企业版**
    -   发布方式：大屏加密发布。
    -   数据源种类：除了基础版支持的数据源种类外，还包括 Oracle 和 SQL Server 等更多种数据接入方式。
    -   组件和模板种类：不限组件使用数量，不限模版使用数量。同时支持外接组件库，例如 ECharts 和 G2 等。
    -   项目数量：支持创建 20 个大屏项目，还可通过购买扩屏包增加可用的大屏数。
    -   其它说明：使用 DataV 制作的大屏，最终会以网页形式发布，而这个网页会包含企业的业务信息。由于网页发布在官网上，不少企业对大屏加密发布有很强烈的需求。而企业版支持用户对大屏进行密码验证和 token 验证两种保密举措，防止业务信息被非相关人士窃取。
-   **开发者版（邀测中）**
    -   发布方式：大屏加密发布。
    -   数据源种类：除了基础版支持的数据源种类外，还包括 Oracle 和 SQL Server 等更多种数据接入方式。
    -   组件和模板种类：不限组件使用数量，不限模版使用数量。同时支持外接组件库，例如 ECharts 和 G2 等。
    -   项目数量：支持创建 20 个大屏项目，还可通过购买扩屏包增加可用的大屏数。
    -   其它说明：开发者版涵盖了企业版的全部功能，并在企业版的基础上，开放组件的二次开发接口，开发者可以根据规范将自己开发的 Javascript 组件接入到 DataV 产品当中，这样即可像使用原生 DataV 组件一样进行便捷的拖拽布局与数据接入。还可以选择将自己的组件库在 DataV 插件市场当中公开售卖，收入归您所有。DataV 开发者版目前面向企业版用户开放体验，详情参见[开发者版的使用](https://yq.aliyun.com/articles/255154?spm=a2c4g.11186623.2.4.Neb5Ah)。
-   **本地部署版**
    -   发布方式：大屏加密发布。
    -   数据源种类：除了基础版支持的数据源种类外，还包括 Oracle 和 SQL Server 等更多种数据接入方式。
    -   组件和模板种类：不限组件使用数量，不限模版使用数量。同时支持外接组件库，例如 ECharts 和 G2 等。
    -   项目数量：支持创建 20 个大屏项目，还可通过购买扩屏包增加可用的大屏数。
    -   其它说明：本地部署版涵盖了企业版的全部功能，并在企业版的基础上，支持用户连接局域网内的数据源、将大屏部署到局域网内，或者将大屏发布到自有域名之下，脱离阿里云的环境。

