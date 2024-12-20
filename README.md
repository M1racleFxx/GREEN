# Дз1
## Задание 1

### Файл primes_sum.py
```
num = int(input("Enter a number: "))
summ = 0

for i in range(2,num+1):
    summ = summ + i

print(summ)
```
## Задание 2
### Палиндром
```
s = input("Введите строку: ")

s = s.replace(" ", "").lower()

left = 0
right = len(s) - 1

while left < right:
    if s[left] != s[right]:
        print ("Не палиндром")
        exit()
    left += 1
    right -= 1

print("Палиндром")
```

