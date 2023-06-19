# Python Programming Fundamentals

## Conditions and Branching

1. what is the result of the following: 1=2

- [x] SyntaxError:can't assign to literal
- [ ] False 
- [ ] True



2. What is the output of the following code segment:

```python 
i=6

i<5
```
- [ ] True
- [x] False

3. What is the result of the following: ``` 5!=5 ```
- [x] False
- [ ] True


4. What is the output of the following code segment: ``` 'a'=='A' ```

- [x] False
- [ ] True

5. in the video, if ``` age=18  ``` what would be the result 

- [x] move on
- [ ] you can enter 


6. in the video what would be the result if we set the variable age as follows: ``` age= -10 ```

- [x] go see Meat Loaf
- [ ] move on
- [ ] you can enter
- [ ] move on


7. what is the result of the following:   ``` True  or False ```

- [x] True, an or statement is only False if all the Boolean values are False
- [ ] False


## Loops

1. what will be the output of the following:

```python 
for x in range(0,3):
    print(x)
```


- [x] 0<br>1<br>2<br>
- [ ] 0 <br> 1 <br> 2 <br> 3



2.  what is the output of the following:
```python
for x in ['A','B','C']:
  print(x+'A')
```

- [x] AA <br>BA <br>CA
- [ ] A <br> B <br>  C

3. what is the output of the following:
```python
for i,x in enumerate(['A','B','C']):  
  print(i,x)
```

- [x] 0 A <br> 1 B <br> 2 C
- [ ] AA <br>BB <br> CC


## Functions

1. What does the following function return: ``` len(['A','B',1]) ```?

- [x] 3
- [ ] 2
- [ ] 4

2. What does the following function return: ``` len([sum([0,0,1])]) ``` ?

- [x] 1
- [ ] 0
- [ ] 3

3. What is the value of list L after the following code segment is run  :
```python
L=[1,3,2]

sorted(L)
```
- [x] L:[1,3,2]
- [ ] L:[1,2,3]
- [ ] L:[0,0,0]

 

4. From the video what is the value of c after the following:
```python
c=add1(2)

c=add1(10)
```
- [ ] 3
- [x] 11
- [ ] 14

5. what is the output of the following lines of code:
```python
def Print(A):   

 for a in A: 

    print(a+'1')

Print(['a','b','c'])
```

- [ ] a <br> b <br> c
- [x] a1 <br> b1 <br> c1
- [ ] a1


## Exception Handling

1. Why do we use exception handlers?

- [ ] Read a file
- [x] Catch errors within a program
- [ ] Terminate a program
- [ ] Write a file

2. What is the purpose of a try…except statement?

- [ ] Executes the code block only if a certain condition exists
- [x] Catch and handle exceptions when an error occurs
- [ ] Crash a program when errors occur
- [ ] Only executes if one condition is true


## Objects and Classes

1. What is the type of the following?

``` ["a"] ```
- [ ] str
- [x] list

2. What does a method do to an object? 

- [x] Changes or interacts with the object
- [ ] Returns a new values 

3. We create the object:

```python
Circle(3,'blue')
```
What is the color attribute set to?

- [ ] 2
- [x] 'blue'


4. What is the radius attribute after the following code block is run?
```python
RedCircle=Circle(10,'red')

RedCircle.radius=1
```
- [ ] 10
- [x] 1
- [ ] 'red'

5. What is the radius attribute
after the following code block is run?
```python
BlueCircle=Circle(10,'blue')

BlueCircle.add_radius(20)
```
- [ ] 10
- [ ] 20
- [x] 30

