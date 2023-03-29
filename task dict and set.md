```python
myset={1,2,6,44.5}
print(myset)
type(myset)
```

    {1, 2, 44.5, 6}
    




    set




```python
my={1,3,5,7,9}
my.add('s')
print(my)
```

    {1, 3, 5, 7, 9, 's'}
    


```python
rem={1, 3, 5, 7, 9, 's'}
rem.discard('s')
print(rem)
```

    {1, 3, 5, 7, 9}
    


```python
se={1,2,33,33,1,5,'mango',4.5}
se1={55,8,1,33,'lemon','demon'}
x=se.intersection(se1)
y=se.union(se1)
z=se1.difference(se)
v=se1.symmetric_difference(se)
print(x)
print(y)
print(z)
print(v)
```

    {1, 33}
    {1, 2, 33, 4.5, 5, 8, 'lemon', 55, 'demon', 'mango'}
    {8, 'demon', 'lemon', 55}
    {2, 4.5, 5, 8, 'lemon', 55, 'demon', 'mango'}
    


```python
new={'akash',11,33,44,3}
new1={11,99,88,77,'aksh'}
x=new1.issubset(new)
print(x)
```

    False
    


```python
a={'akash',11,33,44,3}
b=a.copy()
print(b)
```

    {33, 3, 'akash', 11, 44}
    


```python
rem={'akash',11,33,44,3}
rem.clear()
print(rem)
```

    set()
    


```python
le={1,2,3,4,5,6,7,8,9,10}
a=len(le)
print(a)
```

    10
    


```python
di={'movie':'avathar','year':2010,'director':'james camron'}
di.update({'collection':1000000})
print(di)
```

    {'movie': 'avathar', 'year': 2010, 'director': 'james camron', 'collection': 1000000}
    


```python
fi={'movie': 'avathar', 'year': 2010, 'director': 'james camron', 'collection': 1000000}
fi.pop('collection')
print(fi)
```

    {'movie': 'avathar', 'year': 2010, 'director': 'james camron'}
    


```python
new={'name':'akah','age':21}
new.update({'job':'data scientist'})
print(new)
```

    {'name': 'akah', 'age': 21, 'job': 'data scientist'}
    


```python
com={1,2,3,4,5,6,7,8}
com2={2,4,6,8,10,12}
x=com.intersection(com2)
print(x)
b=len(x)
print(b)
if b>0:
    print("Two sets have common elements")
else:
    print("no elements in common")
    
```

    {8, 2, 4, 6}
    4
    Two sets have common elements
    


```python
com={1,2,3,4,5,6,7,8}
com2={9,10,11,12}
x=com.intersection(com2)
print(x)
b=len(x)
print(b)
if b>0:
    print("Two sets have common elements")
else:
    print("no elements in common")
```

    set()
    0
    no elements in common
    


```python
it={1,2,3,4,5,6,7,8}
for i in it:
    print(i)
```

    1
    2
    3
    4
    5
    6
    7
    8
    


```python
y={10:10,2:2,3:3}
sum(y.values())

```




    15




```python
y={10:10,2:2,3:3}
s=y.values()
print(s)
sm=0
for i in s:
    sm=sm+i
print(sm)
    
```

    dict_values([10, 2, 3])
    15
    


```python
d={15:10,6:2,7:3}
m=y.values()
print(m)
mp=1
for i in m:
    mp=mp*i
print(mp)
```

    dict_values([10, 2, 3])
    60
    


```python

```
