
1. What is the output of the following code?

```python
x="Go"

if(x=="Go"):

  print('Go ')

else:

  print('Stop')
```


- [x] Go Mike
- [ ] Mike
- [ ] Stop Mike

2. What is the result of the following lines of code?

```python
x=1
x>5
```
- [ ] True
- [x] False

3. What is the output of the following few lines of code?
```python
x=0
while(x<2):
    print(x)
    x=x+1   
```
- [x] 0 <br>1
- [ ] 0 <br>1<br>2
- [ ] 0 <br> 1 <br>3<br>4


4. What is the result of running the following lines of code ?

```python
class Points(object):
  def __init__(self,x,y):

    self.x=x
    self.y=y

  def print_point(self):

    print('x=',self.x,' y=',self.y)

```
- [ ] x=1;
- [x]  x=1 y=2
- [ ]  y=2

5. What is the output of the following few lines of code?

```python
for i,x in enumerate(['A','B','C']):
    print(i+1,x)
```
- [x] 1 A <br>2 B <br>3 C
- [ ] 0 A <br> 1 B <br>2 C
- [ ] 0 AA <br> 1 BB <br>2 CC

6. What is the result of running the following lines of code ?

```python
class Points(object):

  def __init__(self,x,y):

    self.x=x
    self.y=y

  def print_point(self):

    print('x=',self.x,' y=',self.y)
```

- [ ] x= 1 y=2
- [x] x= A  y=2
- [ ] x=A, y=B

7. Consider the function step, when will the function return a value of 1?

```python
def step(x):
    if x>0:
        y=1
    else:
        y=0
    return y
```
- [x] if x is larger than 0
- [ ] if x is equal to or less then zero
- [ ] if x is less than zero 

8. What is the output of the following lines of code?

```python
a=1

def do(x):
    return(x+a)

print(do(1))
```
- [x] 2
- [ ] 1
- [ ] NameError: name 'a' is not defined

9. Write a function name add that takes two parameter a and b, then return the output of  a + b (Do not use any other variable! You do not need to run it. Only write the code about how you define it.)
Solution: 
```python
def add(a, b):
    return a + b
```

10. Why is it best practice to have multiple except statements with each type of error labeled correctly?

- [ ] Ensure the error is caught so the program will terminate
- [x] In order to know what type of error was thrown and the location within the program
- [ ] To skip over certain blocks of code during execution
- [ ] It is not necessary to label errors


