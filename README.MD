用Markdown格式在GitHub绘制UML图
====

[comment]: # ( 来源参考: https://stackoverflow.com/a/32771815/1474291 )

![Class Diagram](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/FKLostLand/TestMarkdown/master/MyTestUMLInstance.puml)

Markdown代码
----

* [UML/Instance.puml][1]

[1]: https://raw.githubusercontent.com/FKLostLand/TestMarkdown/master/MyTestUMLInstance.puml

```
Instance <|-- VulkanRootObject

class Instance {
    -- Contructors & destructors --
    - Instance()
    
    -- Public methods --
    + Initialize() : bool
}
```

相关链接
----

1. PlantUML代理链接:
    * http://www.plantuml.com/plantuml/proxy?src=
2. Raw文件链接:
    * https://raw.githubusercontent.com/FKLostLand/TestMarkdown/master/MyTestUMLInstance.puml
3. URL拼接:
    * http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/FKLostLand/TestMarkdown/master/MyTestUMLInstance.puml

源码
----

```
![Class Diagram](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/FKLostLand/TestMarkdown/master/MyTestUMLInstance.puml)
```

