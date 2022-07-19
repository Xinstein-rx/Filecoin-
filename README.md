# Filecoin文档备份插件

## 项目名称

Filecoin文档备份插件

## 项目概述

1. 本项目基于Filecoin和WPS加载项，实现了一款嵌入在WPS内部的文档备份插件WPS加载项类似于一个WPS插件，可以帮助快捷的操作文档，帮助处理复杂的文档内容，实现文档重要内容的标记，对标记数据的修改，实现公文套红头等功能，并可以将修改的文件上传至Filecoin节点，实现持久化存储，并且不能纂改文档内容。
2. 公文场景下有不可被修改的要求，而IPFS&Filecoin正好具有这种特性，二者是完美的结合，当然不只是公文场景，任何文档场景均可利用该特性。
3. Filecoin的功能作为插件嵌入WPS，依托于WPS强大的用户基础，用户看到此功能就有尝试的可能，减少了前期用户冷启动成本。


## 项目运行

项目运行需要保证安装最新款WPS软件，并且全局安装wpsjs开发工具包

### wpsjs工具包安装命令
```
npm install -g wpsjs
```

### 项目运行命令

进入到项目所在目录

```
wpsjs debug
```

即可自动打开WPS文档，体验加载项功能
