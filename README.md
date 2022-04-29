# Reverse-number

number=1234
reverse_number=0
while number!=0:
digit=number%10
reverse_number=reverse_number*10+digit
number//=10
print("reverse number:"+str(reverse_number))
