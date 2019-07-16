# Python-课程学习练习专用
#Python课程第二课练习
#刘大拿老师很幽默，容易记住，容易学会！
#导入全部关键字和注释和变量
import keyword
#打印出全部关键字，关键字不可用做于变量
print(keyword.kwlist)#系统会忽略这些注释的
"""此处纯属练习注释符号
练习，练习
"""
'''
继续练习单引号，谢谢！
练习单引号
'''
"""把符号放在同行末尾试下,也是OK的"""
#定义变量age,赋值单个变量
age=27
print(age)

#定义多个变量，，并相同赋值
age1=age2=age3=age4=age5=age6=28
print(age1)
print(age2)
#一行内多个变量赋值，
#大拿老师说，系统会跳过所有的注释的,只是想多练习一下
age22,age99,age100=12,19,66
print(age22)
print(age99)#当然，小勇子的年龄是19哈，可能吗？哈哈
print(age100)

