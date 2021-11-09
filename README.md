# JavaDeserialization
java反序列化学习笔记

# 说明
我这里只写重点，想学的建议自己debug过一遍。
学习路径推荐：
http://scz.617.cn:8/web/202005261453.txt

# readObject源码分析

# URLDNS
最适合新手分析的反序列化链，完全吃透按顺序开始下面的学习。


# cc链
基础，很多漏洞都需要用到。   
cc链是指依赖Commons-Collections组件构造出来的反序列化利用链。    
Commons-Collections组件主要有两大版本：cc3和cc4。   
这里新手容易绕晕，这两个是完全独立的包。4出来的原因好像是大佬们觉得3写的不好，直接重构了一个全新版本。    

cc3
```
<dependencies>
  <dependency>
    <groupId>commons-collections</groupId>
    <artifactId>commons-collections</artifactId>
    <version>3.1</version>
  </dependency>
</dependencies>
```

cc4
```
<dependencies>
  <dependency>
    <groupId>org.apache.commons</groupId>
    <artifactId>commons-collections4</artifactId>
    <version>4.0</version>
  </dependency>
</dependencies>
```


## cc1
重点，动态代理和反射要学好，不然很吃力。知识点非常多。

## cc2 




