# n_natural_num_in_a_dict
d={}
n=int(input())
for i in range(1,n+1):
  r=0
  for j in range(1,i+1):
    r=r+j
  d[i]=r
print(d)
