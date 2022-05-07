# assignment-1-07-05-2022
#program to store 'no' for odd keys and 'yes' for even numbers and display them,ex:{1:no,2:yes,3:no,4:yes}
n=int(input())
l=[]
d={}
for i in range(n):
    x=int(input())
    l.append(x)
j=1
for i in l:
    if i%2==0:
        d[i]='yes'
    else:
        d[i]='no'
print(d)



output:
==================== RESTART: C:/Python37/dictionary1.py ====================
5
25
56
78
95
88
{25: 'no', 56: 'yes', 78: 'yes', 95: 'no', 88: 'yes'}
