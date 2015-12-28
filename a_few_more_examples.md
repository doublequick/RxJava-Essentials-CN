# 再多几个例子

在这一节中，我们将基于RxJava的`just()`,`repeat()`,`defer()`,`range()`,`interval()`,和`timer()`方法展示一些例子。

## just()

假如我们只有3个独立的AppInfo对象并且我们想把他们转化为Observable并填充到RecyclerView的item中：
```java
List<AppInfo> apps = ApplicationsList.getInstance().getList();

AppInfo appOne = apps.get(0);

AppInfo appTwo = apps.get(10);

AppInfo appThree = apps.get(24);

```