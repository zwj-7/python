# python
根据表结构进行造数
表结构格式为：
字段名称	字段类型
sno	string
name	string
score	bigint
zhanbi	decimal
create_date	timestamp
zhuce_date	date


最后生成的结果为：
sno	name	score	zhanbi	create_date	zhuce_date
24156709	王生安	88	0.22	2020/1/28 8:03	2020/1/25
12332669	潘恩依	94	0.499	2020/1/29 20:45	2020/1/29
79158076	刘昼星	73	0.482	2020/1/25 5:54	2020/1/27
31415211	易江维	57	0.149	2020/1/27 21:57	2020/1/29
49830911	张淮森	84	0.998	2020/1/25 9:48	2020/1/26
32654870	蔡容富	66	0.258	2020/1/26 0:40	2020/1/29
93251781	何刚名	94	0.716	2020/1/28 13:08	2020/1/28
56184216	李富	100	0.254	2020/1/27 21:06	2020/1/27
48796688	张三	77	0.781	2020/1/29 12:38	2020/1/28
83025150	周杰	66	0.951	2020/1/29 11:39	2020/1/27

运行过程为：
D:\anaconda3\python.exe E:/pycharm_workspace/zaoshu.py
造数的条数：16
6
start produce sno column data
data type is string
该列是否为姓名列：yes or no:no
输入字符串的类型：1 字符串中包含数字和字母，2 字符串中只含有数字，3 字符串中只含有字母2
输入字符串的长度：8
start produce name column data
data type is string
该列是否为姓名列：yes or no:yes
start produce score column data
data type is bigint
输入整型数值的最小值：50
输入整型数值的最大值：100
start produce zhanbi column data
data type is decimal
输入整数部分的最小值：0
输入整数部分的最大值：1
输入小数部分的位数：3
start produce create_date column data
data type is timestamp
start produce zhuce_date column data
data type is date
造数成功
转置成功
转为dataframe成功

Process finished with exit code 0

