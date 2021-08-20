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
---
## Day3

### Even numbers from 1 to n
``` python
n=int(input('enter n value: '))
for i in range(0,n):
    if i%2==0:
        print(i)       
```
``` python
num=int(input("enter a num value: "))
for i in range(0,num,2):
    print(i)
```    
---
### Linear search
``` python

array=[1,2,3,4,5,6,9]
index=-1
num=int(input('enter a number: '))
for i in range(len(array)):
    if num==array[i]:
        print(num,'is at index',i)
        index=i
        break
if index<0:
    print('element is not found')
```
---
### separate odd and even numbers from an array
``` python
list1=[1,3,5,8,19,4,10,12,16,13]
even=[]
odd=[]
for i in range(len(list1)):
    if list1[i]%2==0:
        even.append(list1[i])
    else:
        odd.append(list1[i])
print(even)
print(odd)
```
### double each element in an array
``` python
list1=[1,3,5,8,19,4,10,12,16,13]
list2=[]
for i in range(len(list1)):
    list2.append(list1[i]*2)
print(list2)
```
    
    
    

  
