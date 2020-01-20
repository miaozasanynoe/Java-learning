####JAVA常用命令
> 1.javac

    编译代码（即将.java文件编译成.class的中立字节码文件）。使用举例：

```
javac Hello.java
```

> 2.java
    
    解释代码。（注意这个地方不需要.class后缀）使用举例： 
    
```
java Hello
```
> 3.javap
    
    反编译，也可查看Java编译器生成的字节码。（注意这里不需要.class后缀）使用举例：
```
javap Hello
```
> 4.javadoc

    生成文档。
    -d 指定API文档的输出目录，默认是当前目录。建议总是指定该参数。
    -sourcepath 指定源代码路径，默认是当前目录。此参数通常是必须的。
    -subpackages 以递归的方式处理各子包。关键参数！如果不使用本参数，每次只能处理一个
    子包（或需手工列出所有子包）。
    使用举例：
    
```
 javadoc -d javadoc Hello.java
```
    运行如图
    ![javadoc图片]()
    点击链接即可以访问文档，
> 5.多个文件同时操作

