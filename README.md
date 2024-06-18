# large_num
def large(num):
   large=0
   for i in num:
     if i>num:
       large=i
   return large
num=[1,4,2,5,3]
largenum=large(num)
print(largenum)
