# Assignment-01-may-09-2022
n=int(input("Enter the number"))
d={}
for i in range(n):
    x=input().split()
    d[x[0]]=x[1]
while True:
    name = input()
    if name in d:
        print(name,'=',d[name])
    else:
        print('Not found')
