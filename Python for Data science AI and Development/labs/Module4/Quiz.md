
### Module 4 Graded Quiz

1. What is the result of the following lines of code?

```python
a=np.array([-1,1])
b=np.array([1,1])
np.dot(a,b) 
```

- [ ] 1
- [ ] array([0,2]) 
- [x] 0

2. How do you perform matrix multiplication on the numpy arrays  A and  B ?

- [ ] A*B
- [ ] A+B
- [x] np.dot(A,B)

3. What values does the variable  out take if the following lines of code are run?

```python

X=np.array([[1,0,1],[2,2,2]]) 
out=X[0:2,2]
out
```
- [ ] array([1,0])
- [x] array([1,2])
- [ ] array([1,1])

4. What is the value of  Z after the following code is run?

```python

X=np.array([[1,0],[0,1]])
Y=np.array([[2,1],[1,2]]) 
Z=np.dot(X,Y)
```
- [x] array([[2,1],[1,2] ])
- [ ] array([[2,0],[1,0]])
- [ ] array([[3,1],[1,3] ])

5. Consider the following text file:  Example1.txt:

This is line 1

This is line 2

This is line 3

What is the output of the following lines of code?

```python

with open("Example1.txt","r") as File1:

    file_stuff=File1.readline ()

    print(file_stuff)

```
- [x] This is line 1 
- [ ] This is line 1 <br> This is line 2 <br> This is line 3
- [ ] This is line 1 <br> This is line 2

6. What do the following lines of code do?

```python

with open("Example1.txt","r") as file1:
  
  FileContent=file1.readlines()

  print(FileContent)
```

- [x] Read the file "Example1.txt"
- [ ] Write to the file “Example1.txt”
- [ ] Append the file "Example1.txt"

7. What do the following lines of code do?

```python

with open("Example.txt","a") as writefile:
  
  writefile.write("This is line A\n")
  writefile.write("This is line B\n")
```
- [ ] Write to the file “Example.txt”
- [ ] Read the file "Example.txt"
- [x] Append the file "Example.txt"

8. What task do the following lines of code perform?

```python

with open('Example2.txt','r') as readfile:
    with open('Example3.txt','w') as writefile:
          for line in readfile:
                writefile.write(line)
```

- [x] Copy the text from Example2.txt to Example3.txt.
- [ ] Print out the content of Example2.txt.
- [ ] check the mode of the open function for each file object.

9. Consider the dataframe df. How would you access the element in the 2nd row and 1st column?

- [x] df.iloc[1,0]
- [ ] df.iloc[2,1]
- [ ] df.iloc[0,1]


10. In the lab, you learned you can also obtain a series from a dataframe df, select the correct way to assign the column with the header Length to a pandas series to the variable x.

- [x] x=df['Length']
- [ ] x=df[['Length']]
- [ ] x=df.[['Length']]


