a=-1
b=1
sum=0
n=int(input())
for i in range(1,n+1):
    c=a+b
    print(c)
    a=b
    b=c
    sum=sum+i
print(sum)    
    
