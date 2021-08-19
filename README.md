# python
---

## Day1
### Even number or Odd
```python
num=int(input("enter number:"))
if num%2==0:
    print(num,'is even')
else:
    print(num,'is odd')
```

---

### check_palindrome number

```python

x=int(input("enter a number: "))
temp=x
reverse=0
while(x>0):
    rem=x%10
    reverse=reverse*10+rem
    x=x//10
if temp==reverse:
    print(temp,'is a palindrome number')
else:
    print(temp,'is not a palindrome number')
```
---
## Day2
### swapping two numbers
---
```python
a=10
b=20
print('Before swapping a :',a,'&& b:',b)
temp=a 
a=b 
b=temp 
print('After swapping a :',a,'&& b:',b)
```
---
### largest of three numbers
``` python
a=int(input('enter a value: '))
b=int(input('enter b value: '))
c=int(input('enter c value: '))
if a>b:
    if a>c:
        print(a,'is greater')
    else:
        print(c,'is greater')
elif b>c:
    print(b,'is greater')
else:
    print(c,'is greater')
```
---
### odd numbers from 1 to n
``` python
n=int(input('enter n value ')
for i in range(1,n):
    if i%2!=0:
        print(i)
```
``` python
n=int(input("Enter the number: \n"))
for i in range(1,n,2):
    print(i)
```
