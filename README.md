# zavdannya-2
# Сума першої і останньої цифр числа
a = int(input())
b = a % 10
sum = 0
while a > 0:
    last_digit = a % 10
    a //= 10
    sum = last_digit + b
print(sum)
