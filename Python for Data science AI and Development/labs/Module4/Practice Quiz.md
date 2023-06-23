### Reading and Writing Files with Python

1. What are the most common modes used when opening a file?

- [ ] (a)ppend, (c)lose, (w)rite
- [ ] (a)ppend, (r)edline, (w)rite
- [ ] (s)ave, (r)ead, (w)rite
- [x] (a)ppend, (r)ead, (w)rite

2. What is the data attribute that will return the title of the file?
- [ ] File1.close()
- [x] File1.name
- [ ] File1.open()
- [ ] File1.mode

3. What is the command that tells Python to begin a new line?
- [x] \n
- [ ] \b
- [ ] \e
- [ ] \q

4. What attribute is used to input data into a file?

- [ ] File1.read()
- [x] File1.write()
- [ ] File1.close()
- [ ] File1.open()



### Pandas


1. What python object do you cast to a dataframe?

- [ ] set
- [ ] tuple
- [x] dictionary

2. How would you access the first-row and first column in the dataframe df?
- [x] df.ix[0,0]
- [ ] df.ix[0,1]
- [ ] df.ix[1,0]

3. What is the proper way to load a CSV file using pandas?

- [ ] pandas.from_csv(‘data.csv’)
- [ ] pandas.load_csv(‘data.csv’)
- [x] pandas.read_csv(‘data.csv’)
- [ ] pandas.import_csv(‘data.csv’)

4. Use this dataframe to answer the question.

<img src="https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/vagPiMX7QReoD4jF-1EXEA_fea446fc19b84f128bdd4275743610eb_Pandas_1.png?expiry=1687651200000&hmac=laONyGvriVxem_rD8chhCrKvqLzHZOVR-2BNtJq-qxg">

How would you select the Genre disco? Select all that apply.

- [ ] df.iloc[6, ‘genre’]
- [ ] df.loc[6, 5]
- [x] df.iloc[6, 4]
- [ ] df.loc[‘Bee Gees’, ‘Genre’]

5. Use this dataframe to answer the question.
<img src="https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/vagPiMX7QReoD4jF-1EXEA_fea446fc19b84f128bdd4275743610eb_Pandas_1.png?expiry=1687651200000&hmac=laONyGvriVxem_rD8chhCrKvqLzHZOVR-2BNtJq-qxg">


Which will NOT evaluate to 20.6? Select all that apply.

- [ ] df.iloc[4,5]
- [ ] df.iloc[6,5]
- [x] df.loc[4,’Music Recording Sales’]
- [x] df.iloc[6, ‘Music Recording Sales (millions)’]

6. Use this dataframe to answer the question.

<img src="https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/vagPiMX7QReoD4jF-1EXEA_fea446fc19b84f128bdd4275743610eb_Pandas_1.png?expiry=1687651200000&hmac=laONyGvriVxem_rD8chhCrKvqLzHZOVR-2BNtJq-qxg">

How do we select Albums The Dark Side of the Moon to Their Greatest Hits
(1971-1975)? Select all that apply.

- [ ] df.iloc[2:5, ‘Album’]
- [x] df.loc[2:5, ‘Album’]
- [x] df.iloc[2:6, 1]
- [ ] df.loc[2:5, 1]


### Numpy

1. What is the Python library used for scientific computing and is a basis for Pandas?

- [x] Numpy
- [ ] Tkinter
- [ ] Requests
- [ ] datetime

2. What attribute is used to retrieve the number of elements in an array?

- [x] a.size
- [ ] a.ndim
- [ ] a.shape
- [ ] a.dtype

3. How would you change the first element to "10" in this array ``` c:array([100,1,2,3,0]) ```?

- [ ] c[2]=10
- [ ] c[4]=10
- [x] c[0]=10
- [ ] c[1]=10

4. What attribute is used to return the number of dimensions in an array?

- [ ] a.size
- [ ] a.shape
- [x] a.ndim
- [ ] a.dtype



