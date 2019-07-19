用Markdown格式在GitHub绘制UML图
====

[comment]: # ( 来源参考: https://stackoverflow.com/a/32771815/1474291 )

![Class Diagram](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/Zingam/Markdown-Document-UML-Use-Test/master/UML/Instance.puml)

项目结构
----

```
 |
 +-- UML
 |    |
 |    +-- Instance.puml
 |         ...    
 |
 +-- README.md
      ...
        
```

Markdown代码
----

* [UML/Instance.puml][1]

[1]: https://github.com/Zingam/UML-in-Markdown/blob/master/UML/Instance.puml

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

1. PlantUML's proxy:
    * http://www.plantuml.com/plantuml/proxy?src=
2. Document's GitHub raw URL:
    * https://raw.githubusercontent.com/Zingam/Markdown-Document-UML-Use-Test/master/UML/Instance.puml
3. Combined URL (combine the PlantUML's proxy URL and the document's GitHub raw URL):
    * http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/Zingam/Markdown-Document-UML-Use-Test/master/UML/Instance.puml

