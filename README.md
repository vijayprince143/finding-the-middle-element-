# finding-the-middle-element-n=int(input("enter the size:"))
li=[]
for i in range(n):
    li.append(int(input()))
if(n%2==0):
    #c=int(n/2)-1
    
    print("middle element is ",li[int(n/2)-1])
else:
    print("middle element is ",li[int(n/2)])
