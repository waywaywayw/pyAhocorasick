pyAhocorasick
=============

a pure python Aho-corasick algorithm implementation

以下是中文翻译：
没别的，就是支持unicode utf-8 中文。其他的可参考其他项目，欢迎中国程序男加入。

========================== 以上是原code的readme ==========================

原code是基于python2的，我修改了一些小地方，现在可以运行在python3(3.5.2实测可跑）

例子：
```
	if __name__ == '__main__':
		ah = Ahocorasick()
		ah.addWord(u'测试')
		ah.addWord(u"我是")
		ah.make()
		print( ah.search(u'测试123我是好人'))
```
