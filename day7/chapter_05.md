# Learning Python

## 5. Data Structures
1-more on lists

i-   append(x)- can add an element 
ii-  extend(iterable)- can add whole list
iii- insert(i,x)-herre item x will be iserted at i the place
iv-  pop(i)- ith item will be removed. if no indexis specified removes last item 
v-   clear()- all items are removed
vi-  count()- counts the no times an element occured in list
vii- sort(*, key=None, reverse=False)- sorts the list 
viii-reverse()- 
ix-  copy()
x-   remove(x)-removes x element
xi-  index(x[, start[, end]])

2- can be used as stack(LIFO)

i-  to add an item at top use append() and remove from top use pop()

3- can be used as queue but its slower as all elements will have to be shtfted(FIFO) 

4-List Comprehensions- way of for loop and if else statements in a single line (min lines)
 x=[i if i>12 else  for j in range() for i in range(j)]\
  
  squares = list(map(lambda x: x**2, range(10))) 
  
  above is equivalent to 
  
  squares = [x**2 for x in range(10)]
eg1-
>>>[(x, y) for x in [1,2,3] for y in [3,1,4] if x != y]
[(1, 3), (1, 4), (2, 3), (2, 1), (2, 4), (3, 1), (3, 4)]

eg-2
>>>freshfruit = ['  banana', '  loganberry ', 'passion fruit  ']
>>>[weapon.strip() for weapon in freshfruit]
['banana', 'loganberry', 'passion fruit']

5- del a[0]- will del a[0] from a list a

6- Tuples 

a=(1,2,3,)
a=(1,)-- if it is a single element use comma else will be considered as int

they are immutable,

7- Sets- they do not have duplicate elements

a={1,2,3,4,5,6}
set comprehensions are also supported
>>>a = {x for x in 'abracadabra' if x not in 'abc'}
>>>a
{'r', 'd'}

8-Dictionary- they store data in key value pair

i-   they are indexed by keys-which can be any immutable type; strings and numbers can always be keys not LIST
ii-  keys are unique
iii-The dict() constructor builds dictionaries directly from sequences of key-value pairs:

>>>dict([('sape', 4139), ('guido', 4127), ('jack', 4098)])
{'sape': 4139, 'guido': 4127, 'jack': 4098}

iv- dict comprehensions

>>>{x: x**2 for x in (2, 4, 6)}
{2: 4, 4: 16, 6: 36}


v-how to loop in dict
    for k, v in knights.items():

vi- enumerate()

>>>for i, v in enumerate(['tic', 'tac', 'toe']):
    print(i, v)



vii- zip()-- it zip one iterable with another 
>>>questions = ['name', 'quest', 'favorite color']

>>>answers = ['lancelot', 'the holy grail', 'blue']

>>>for q, a in zip(questions, answers):

    print('What is your {0}?  It is {1}.'.format(q, a))


viii- reversed() used to loop throug a range in reverse order
ix- sorted() -- sorting in str works as first a then b and so on
x-set()- to covert it in set





