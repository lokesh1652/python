# python

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
