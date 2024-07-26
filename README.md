# strong-number
sum=0
num=int(input("enter number"))
temp=num
while num!=0:
    i,f=1,1 
    r=num%10
    while (i<=r):
        f=f*r
        i+=1 
        sum=sum+f
        num=num//10
        if sum==temp:
           print("strong number")
        else:
           print("not")
