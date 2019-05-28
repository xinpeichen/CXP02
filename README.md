# CXP02
from random import randint
x=randint(0,300)
guess=int(input('请输入猜测的数字:'))
if guess==x:
    print('猜对了')
elif guess>x:
    print('猜大了')
else:
    print('猜小了')
