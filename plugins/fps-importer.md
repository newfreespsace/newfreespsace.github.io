# fps-importer

## 从 fps 文件导入题目

在题库右侧“创建题目”一栏中选择“从 FPS 文件导入”。  
在打开的窗口中，您可以上传：

- fps 格式的 xml 文件
- zip 文件，其中包含了一个或多个 fps 格式的 xml 文件

由于防止解析 fps 文件消耗大量内存，系统默认拒绝导入超过 64MiB 的文件;
xml 文件需要为 UTF8 编码，否则可能出现中文题面乱码；
在新版本 fps-importer 中，管理员可以修改导入文件大小限制，但请注意，我们仍不建议您导入过大的题目包。 
若您的文件超过大小限制，可考虑先在本地使用 Easy-Fps-Viewer 等工具进行拆分。