# Existance
# cook your dish here
t=int(input())
while t:
    x,y=map(int,input().split())
    if((x**4)+(4*(y**2))==(4*(x**2)*y)):
        print("Yes")
    else:
        print("No")
    t-=1
