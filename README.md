#n=int(input())

l=input().split()

print(l)

t=[]

for i in l:

    t.append(int(i))

print(t)

x=[]

for i in t:

    if l not in x:

        x.append(i)

print(x)

x.sort(reverse=True)

print(x)

print(x[l])
