##### 获取Unsafe实例

###### 1. 直接获取是不行的

```java
        Unsafe unsafe = Unsafe.getUnsafe();
        System.out.println(unsafe);
```

运行结果如下：

```shell
Exception in thread "main" java.lang.SecurityException: Unsafe
	at sun.misc.Unsafe.getUnsafe(Unsafe.java:90)
	at org.aidan.Client.main(Client.java:12)

Process finished with exit code 1
```

