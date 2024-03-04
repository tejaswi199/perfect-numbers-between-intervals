l=int(input())
u=int(input())
for i in range(l,u+1):
  c=0
  for j in range(1,i):
    if(i%j==0):
      c=c+j
  if(c==i):
    print(i)
