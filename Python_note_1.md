# String
*一些关于字符串的操作 *
> s='spam'
> len(s)

 找出元素引索
> s.find('')

用‘ ’来分割列表中的

> s.split(' ')

将大写字母转为小写
> s.lower()
> s.upper()

判断是否列表中含有数字
> s.isdigit()
>s.isalpha()

删去最末的空白区域元素
> line = 'aaaa,gggg,jjjj\n'
> line=line.rstrip()
> line
> 'aaaa,gggg,jjjj'

格式化（一种高级替代操作）
> '%s,apples,or %s' %('taotie','yu')
> '{0},apples,or %s' .format（'taotie','yu'）

切片
> a='123456'
> print a[1:3]
> print a[0:-2]

还可以设置步长
> a[::2]

指定符号分割一个列表
> a=list(set(‘adsfgsh’))
> print '.'.join(a)





	