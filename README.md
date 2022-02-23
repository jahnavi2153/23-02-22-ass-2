# 23-02-22-ass-2
#write a program to print reverse of the list elements.
l=[]
n=int(input())
for i in range(n):
    x=int(input())
    l.append(x)
l.reverse()
print('reverse of a list',l)

output:
5
45
2
34
78
12
reverse of a list [12,78,34,2,45]
