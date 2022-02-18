# feb-18-ass-1
Assignment-1
def primenum (n):
    for i in range(2,n):
        if n%i==0:
            return True
    return False
     
n=int(input('enter n:'))
c=0
for i in range(1,n):
    if primenum (i):
        c=c+1
print('count', c)

Output:
enter n: 10
count 4
