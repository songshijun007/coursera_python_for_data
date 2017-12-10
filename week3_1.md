##3.1为什么需要字典


一般的字典创建方式是ainfo = {'a':1,'b':2,'c':3},
另外的创建方式为dinfo = dict(a = 1,b = 2,c = 3),

字典默认值的设置：
    adict = {}.fromkeys(('a','b'),3000)#a,b的默认值都为3000.
    
sorted(adict)#显示的是内部存储的顺序，因为字典是无序存储的，所以并不是我们想象的按大小存储。

zip函数可以将两个列表数据组合为字典。

单独输出keys或者values，adict.keys()或者adict.values()

如果要遍历全部的keys和values：for k,v in adict.items()

update函数可以将更改原有信息以及增加新进信息，adict.update(bdict)

adic.get('c')查找字典

如果已经bdict = adict，如果adcit = {}只清除adict，而bdict还保留由adict的内容；
但是如果用adict.clear（）将会把adict以及bdict全部删除。


3.2字典的使用

搜索引擎关键词的查询;
    http://baidu.com/s?wd=%s  #wd=%s就是需要输入的关键字
    kw = {'wd' : 'python dict'}
    r = requests.get('http://baidu.com/',params = kw)
    r.url
    print(r.text)
    
 3.3集合（set）#集合内没有重复的元素
 
    集合是可以进行运算的，或且非
    特别注意的是：a-b意思是属于a的元素但在b中没有，
                 a^b意思是ab中不同有的元素，即各自特有的。
                 
