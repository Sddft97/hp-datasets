# hpDatasets

和yolo5模型文件夹绑定，这两个文件夹的目录结构如下所示。

```
-
--hp
--yolo5-master
```

即两个文件夹同级。



本仓库下暂定有三个文件夹，即

```
-
--images
--labels
--origin
```

*origin*文件夹中存放原始图片数据，标注工作在这个文件夹中进行。

标注完成后，使用转换工具将*json*标签转换为*txt*标签。将标注完的图片放入*images*文件夹中，*txt*标签放入*labels*文件夹中。
