

CTP简化版量化交易系统实现。

## 方案说明

<img src="https://github.com/pleuvoir/pdump/blob/master/docs/CTP%E7%AE%80%E5%8C%96%E4%BA%A4%E6%98%93%E5%B7%A5%E4%BD%9C%E6%B5%81%E7%A8%8B.png" alt="CTP简化交易工作流程" width="780" height="513" align="bottom" />



其中包含三大块需要开发的内容：数据处理平台，回测平台，交易执行程序。

数据处理平台：现在还不确定上期CTP接口（因为我无法访问），可能需要用C++实现，如果有Java API相对来说容易一些，或者做适配？使用JAVA考虑使用XXL-job。持久化使用Mysql、Mongodb或者其他时间序列数据库？

回测平台：使用Java、go、python？

交易执行程序：和回测放在一起？