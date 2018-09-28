# repositoty-pops
a=int(input('请输入数字：'))
a=abs(a)
for x in range(1,a+1,2):
    if a<16:
        print(('^'*x).center(a))
    elif x<(a/3):
        print(('^'*x).center(a))
    elif x<(3*a/4):
        print(('^'*(x-int(a/8)*2)).center(a))
    else:
        print(('^'*(int(a/6)*2-3)).center(a))
