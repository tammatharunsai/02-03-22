A=[]
m=int(input('enter no of rows'))
n=int(input('enter no of column'))
for i in range(m):
    row=[]
    for j in range(n):
        k=int(input())
        row.append(k)
    A.append(row)
print(A)
B=[]
m=int(input('enter no of rows'))
n=int(input('enter no of column'))
for i in range(m):
    row=[]
    for j in range(n):
        k=int(input())
        row.append(k)
    B.append(row)
print(B)
c=[[0,0,0],[0,0,0],[0,0,0]]
for i in range(len(A)):
    for j in range(len(B[0])):
        for k in range(len(B)):
            c[i][j]=c[i][j]+A[i][k]*B[k][j]
print('resultant matrix is:')
for i in range(m):
    for j in range(n):
        print(c[i][j],end=' ')
    print()
