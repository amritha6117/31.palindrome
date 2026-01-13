# 31.palindrome
num = int(input("Enter the number: "))

rev = 0
temp = num

while temp > 0:
    rem = temp % 10
    rev = rev * 10 + rem
    temp //= 10

if rev == num:
    print("It is a Palindrome Number")
else:
    print("It is not a Palindrome Number")
    OUTPUT:
  Enter the number: 4
It is a Palindrome Number
  
