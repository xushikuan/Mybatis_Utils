#Mybatis工具类

作者博客：http://blog.csdn.net/isea533

作者QQ： 120807756

作者邮箱： abel533@gmail.com

Mybatis工具群： 540609123 (Mybatis相关工具插件等等)

##强烈推荐必读文章

- [深入了解MyBatis参数](http://git.oschina.net/free/Mybatis_Utils/blob/master/Blog/%E6%B7%B1%E5%85%A5%E4%BA%86%E8%A7%A3MyBatis%E5%8F%82%E6%95%B0.md)

##通用Mapper

gitosc地址:http://git.oschina.net/free/Mapper

github地址:https://github.com/abel533/Mapper

##分页插件

gitosc地址：http://git.oschina.net/free/Mybatis_PageHelper

github地址:https://github.com/pagehelper/Mybatis-PageHelper

## JdbcType 自动配置插件

运行时自动添加 jdbcType 属性

gitosc地址：http://git.oschina.net/free/Mybatis_Utils/tree/master/JdbcType

##SqlMapper

一个通过MyBatis直接执行SQL的工具，包含详细的文档和设计思路

gitosc地址：http://git.oschina.net/free/Mybatis_Utils/tree/master/SqlMapper

##SqlHelper - 获取sql

gitosc地址：http://git.oschina.net/free/Mybatis_Utils/tree/master/SqlHelper 

相关文章： http://blog.csdn.net/isea533/article/details/40044417

##PerformanceInterceptor
###性能拦截器，用于输出每条 SQL 语句及其执行时间

gitosc地址：http://git.oschina.net/free/Mybatis_Utils/tree/master/Performance

###简单说明：  

性能分析拦截器主要输出Sql以及Sql执行的时间，该拦截器会损失一定的整体性能，所以建议在测试环境使用，正式环境不建议使用。  

另外，如果配置了多个拦截器，那么一定要把这个拦截器配置在第一个，否则其他需要修改Sql的拦截器会对该拦截器获取Sql部分产生影响。  

建议根据个人需求对该拦截器进行修改。    

##CameHumpInterceptor
###返回值Map结果的Key转为驼峰式

例如返回结果中Map的`{REAL_NAME:liuzh}`会转换为`{realName:liuzh}`  

地址：http://git.oschina.net/free/Mybatis_Utils/tree/master/CameHumpMap

##MybatisGeneator详解  

http://git.oschina.net/free/Mybatis_Utils/tree/master/MybatisGeneator/MybatisGeneator.md
