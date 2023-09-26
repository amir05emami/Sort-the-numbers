# Sort-the-numbers
L=[]
while 1:
    num=int(input("enter num:"))
    if num==0:
        break
    L.append(num)
L.sort(reverse=True)


for num in L:
    print(num)
