# patsakpapei
A=[]
while True:
    item = int(input("Enter the items,press -1 to escape:"))
    
    if item == -1:
        break
    
    A.append(item)
mhden=A.count(0)
length=len(A)
print(mhden)
B=[]
for i in range (len(A)):
    if A[i]!=0:
        B.append(A[i])
for i in range(mhden):
    B.append(0)
for i in range (length):
    A[i]=B[i]
        

print(A)
