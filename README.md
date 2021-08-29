# 中文
## 用于应对更新版本导致static发生变化的工具


### 使用方法
1、解压并打开 main.exe 。


2、在右上角的菜单中选择 生成字典文件 ，需要旧版本未翻译的原文本与译本，生成的字典文件会位于 ./source_file/dict 。


3、生成完成后选择 翻译原始语言文件 ，选择当前版本的原文本，生成的新文本位于 ./source_file/output 。

### 备注
1、生成字典文件 中，会优先以未翻译的原文本生成字典的文件名，即原文件名为 static.json 则会生成 static_dict.json。

2、翻译原始语言文件 中，请保证原文件名与旧版本的原文件名相同（程序会自动查询）。


3、生成的新语言文件中，文件名与原文件名相同的为已翻译词条的集合，前缀为 neededTranslate_ 的为未翻译词条的集合。后缀为 _all 的为两者的集合但是按照原文件的顺序进行排序。

### 已知问题
-生成字典文件中 并无法同时进行多个语言文件的同时生成因此默认选否。


-路径选择后的显示，多个文本框会保持最后一次选择的结果，不影响正常使用。


-选择功能后或输入路径后，新的显示框体并未置顶，需要手动切换。
