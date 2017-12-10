3.2_1扩展数据库scipy
     
     numpy
     
     numpy.fromfunction(lamda i,j:(i+1)*(j+1),(9,9))#创建一个九九乘法口诀表，lamda是匿名函数
     
     #（9,9）分别给i，j从0-8赋值
     
     Aarray.reshape(1,2)#只是改变输出格式，并没有改变Aarry的格式
     
     Aarray.resize(1,2)#真正改变Aarry格式
     
     np.vstack(Aarray,Barray)#在竖直方向拼接数组
     
     np.hstack(Aarray,Barray)#在水平方向拼接数组
     
     Aarray.sum(axis = 0)#按行进行求和
     
     Aarray.sum(axis = 1)#按列进行求和
     
     
