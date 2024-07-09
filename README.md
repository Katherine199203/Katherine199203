#我也愛偶數
a,b = input().split()
a = int(a)
b = int(b)
total = 0
        
if 0<=a<=b<=2147483647:
        for num in range(a,b):
          if num %2 ==0:
        total += num
        print(total)
else:
  print("erro")
