# numpy-学习笔记
1.numpy.array()创建向量或矩阵
2.print(a.shape) 输出a向量（或矩阵）的形状 a.shape = 6,2 设置a的形状
3.a.dtype（a.dtype.name） 输出a向量（或矩阵）的形式，如int32 float64
4.a.min（）
5.a.sum(axis = 0),a.sum(axis = 1),按列(按行)进行求和
6.numpy.arange(n)生成0~n-1的数列
7.numpy.arange(15).reshape(3,5)生成3x5矩阵
8.a.ndim 输出a的维度
9.a.size 输出a中元素的个数
10.numpy.zeros((3,4))生成3X4的零矩阵同样有numpy.ones((3,4))
11.numpy.arange(10,30,5)生成10~30间距为5数列
12.numpy.random.random((2,3)) 随机生成2X3矩阵
13.numpy.linespce(0,3.14*2,100)生成0~3.14*2的数列，均分100份
14.+-*均可用于矩阵运算(*为内积)
15.print(a.dot(b))打印a矩阵与b矩阵的乘积,同numpy.dot(a,b)
16.numpy.exp(a),numpy.sqrt(a)
17.a.ravel()将多维数组降至1维，a.T对a进行转置
18.a.floor()计算每个元素的地板值
19.numpy.vstack(a,b),numpy.hstack(a,b),将a，b纵向（横向）进行拼接;numpy.hsplit(a,3)维度方向切分为3份
20.c = a.view 浅拷贝,c=a.copy()
21.ind = a.argmax(axis = 0)按列寻找最大值的index
22.a.sort(axis=1) 按行进行排序 同numpy.sort(a,axis=1),numpy.argsort(a)输出a排序后index的矩阵
