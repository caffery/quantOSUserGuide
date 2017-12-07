# quantOS可以做什么?

作者：quantOS.org

quantOS致力于提供量化开源系统的一站式解决方案.

## quantOS有哪些特点

*  **完全开源**.所有软件完全开源, 用户可以免费使用.
*  **免费数据**.提供策略研究必须的、高质量的、可持续的研究数据,
*  **本地策略**.提供包括Alpha、CTA、套利等策略模板和回测框架，用户可以快速实现策略，本地化部署。
*  **仿真交易**.提供免费在线仿真交易模拟环境，帮助用户进行策略验证。
*  **实盘交易**.提供多种成熟的实盘交易解决方案，适用不同的用户。

## quantOS的业务框架

quantOS推荐的量化交易的业务框架如下图所示：![](https://github.com/quantOS-org/quantOSUserGuide/blob/master/assets/framework.png?raw=true)主要涉及三个核心的业务组件：数据、策略和交易。

quantOS业务框架以策略研究平台JAQS为核心，通过标准化的数据Api(DataApi)和交易Api(TradeApi)，将数据、策略、交易的连接打通，提供了一站式的解决方案。

**在数据系统上**，quantOS提供两种选择：

* 通过与tushare深度集成，提供在线数据服务(data.tushare.org)。
* 开源DataCore数据系统，客户可适配自己的数据源，本地化部署。

**在策略系统上**，JAQS策略系统采用Python开发并完全开源，并提供了规范化的研究流程和常见类型策略的支持，提供回测框架。用户可下载到本地后，实现自己的策略，保障客户的策略安全。

**在交易系统上**，quantOS提供多种选择：

* 提供一个在线仿真服务TradeSim，供用户策略验证的有效性。
* 实现了与vn.py的深度集成，可通过vn.py进行实盘交易。
* 使用企业版的交易软件TKPro进行实盘交易。

