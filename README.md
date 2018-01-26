`mat2ifw_Auto.py` 会按照 @蠢黑通行 的方法识别并分类生成 IFW：

> 使用了 `broadcast`、`service`、`activity` 关键字来判断组件属性，将其两边加上前缀和后缀，并分别粘贴至三个不同的新建文档，最后按顺序将其合并。如果有不按标准命名的组件，会将其写在最底部，需人工操作解决，可以将光标停留在任意一行，分别将该行组件插入 `服务` | `广播` | `活动` 分组。这种方法处理的 IFW 文件比较简洁，不过就是需要手动操作一下部分遗漏的组件。

`mat2ifw_Easy.py` 则会将所有值在每个节点中复制一份来生成 IFW 文件：

> 先在两边加上前缀和后缀，后将整个 MAT 方案复制两遍然后在将 IFW 用于判定 `broadcast`、`service`、`activity` 属性的语句，重复三遍。

`mat2ifw_Easy.py` 的在线版：[https://apkjam.github.io/IFW/mat2ifw.html](https://apkjam.github.io/IFW/mat2ifw.html)

（via [link](https://bbs.letitfly.me/d/100)）
