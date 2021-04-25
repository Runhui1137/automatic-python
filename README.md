# automatic-python
use python to create some automatic tools for convenience
### word-name-formatter 实验报告文件名格式化器
我常为同学们提交实验报告时文件名不统一而感到烦恼, 一个个地修改是一件很麻烦的事. 
于是我写了一个"实验报告格式化器", 用了它, 以后收word的时候再也不用为此而焦虑了.  
#### (最简单快捷的)使用方法
1. 将你们班的同学信息以.csv格式文件导出, 并保证第一列为学号
2. 修改.py文件中的相关配置信息(你的.csv文件位置, 你的实验报告所处目录, 你的同学学号的正则表达式)
3. 运行程序, 程序将自动为doc和docx文件重命名
#### 注意事项: 
1. doc文件无法直接读取, 因此在读取之前进行另存, 另存目录为./temp文件夹, 程序运行完毕后可手动删除
2. 这个程序很简单, 如果会一点python编程, 相信你会有更多的食用方法
3. 本程序乃本人受实验报告重命名所困扰, 一气之下而成, 并不完善, bug可能也很多. 若此程序有幸为您效劳, 遇到bug还请息怒(还请原谅我的锅>_<)
