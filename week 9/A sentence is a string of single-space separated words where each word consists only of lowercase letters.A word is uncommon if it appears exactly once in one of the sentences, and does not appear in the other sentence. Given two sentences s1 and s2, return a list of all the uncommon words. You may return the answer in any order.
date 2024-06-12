a=input()
b=input()
s=a+' '+b
z=s.split()
d=dict()
for i in range(0,len(z)):
    if z[i] not in d:
        d[z[i]]=1
        for j in range(i+1,len(z)):
            if z[i]==z[j]:
                d[z[i]]=d[z[i]]+1
    
for i in d:
    if d[i]==1:
        print(i,end=' ')
