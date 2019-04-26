### gp-learn-mybatis

#### 1、resultType和resultMap的区别？
**resultType可以指定返回的类型如String,Integer,List,Map,Object等**  
**resultMap分为嵌套结果与嵌套查询**

#### 2、collection和association的区别？
**collection处理对象模型中一对多的对象属性**  
**association处理对象模型中一对一的对象属性**

#### 3、Statement和PreparedStatement的区别？
**Statement sql拼接，有sql注入的危险。并且每次都要编译。性能消耗多**  
**PreparedStatement 预编译处理，防止sql注入，可以重用**



