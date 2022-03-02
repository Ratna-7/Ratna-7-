#program to print multiplication of 2 matrices:
A=[]
m=int(input('enter no.of rows:'))
n=int(input('enter no.of columns:'))
for i in range(m):
    row=[]
    for j in range(n):
        k=int(input())
        row.append(k)
    A.append(row) 
print(A)    
B=[]
m=int(input('enter no.of rows'))
n=int(input('enter no.of columns:'))
for i in range(m):
    row=[]
    for j in range(n):
        k=int(input())
        row.append(k)
    B.append(row)
print(B)
result=[[0,0],[0,0]]
for i in range(m):
    for j in range(n):
        for k in range(n):
            result[i][j]+=A[i][k]*B[k][j]
print('resultant matrix is:')
for i in range(m):
    for j in range(n):
        print(result[i][j],end=' ')
    print()
    
    
    OUTPUT:
    enter no.of rows:2
enter no.of columns:2
1
2
3
4
[[1, 2], [3, 4]]
enter no.of rows2
enter no.of columns:2
1
3
4
5
[[1, 3], [4, 5]]
resultant matrix is:
9 13 
19 29
