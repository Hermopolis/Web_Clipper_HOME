## 系统相关
```dataview
list  os 
FROM  "note/os"
sort "ASC"


```

##  网络相关
```dataview
list  network
FROM  "note/network"
GROUP BY file.link
sort "ASC"
```

## java
```dataview
list  java
FROM  "note/java"
GROUP BY file.link
sort "ASC"

```

##  数据库相关
```dataview
list  data-base
FROM  "note/data-base"
GROUP BY file.link
sort "ASC"
```


##  linux相关
```dataview
list  linux
FROM  "note/linux"
GROUP BY file.link
sort "ASC"
```