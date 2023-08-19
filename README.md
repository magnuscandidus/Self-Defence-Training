# Self-Defence-Training
# cook your dish here
t=int(input())
while t:
    x=int(input())
    a=list(map(int,input().split()))
    count=0
    for i in range(len(a)):
        if(a[i]>=10 and a[i]<=60):
            count+=1
    print(count)
    t-=1
        
        
