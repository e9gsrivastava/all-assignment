# Learning Python

## 3. An Informal Introduction to Python
1- >>>  vs   ...
2- #  vs    '#'
3-python interpretor can be used as calcualtor 

check what type we get after operations--
 i-  we get int for *,+,-,//(returns floor value of division),**(sq)
 ii- and float for /
 iii-for any int+float we get type float 
 iv- % return remainder
 v- '=' is used t assaign value,
 vi- '==' is used to compare
 vii- what is this  x+_  (hint gives prev value )
 viii- 3+5j  (here 2nd part is imaginary)

 4- Strings


 i-digits and numerals enclosed in quotes are also strings
    "Paris rabbit got your back :)! Yay!"  
    'Paris rabbit got your back :)! Yay!'

 ii= use of '\'

>>>'doesn\'t'  # use \' to escape the single quote...
"doesn't"

>>>"doesn't"  # ...or use double quotes instead
"doesn't"

>>>"\"Yes,\" they said."
'"Yes," they said.'

>>>'"Isn\'t," they said.'
'"Isn\'t," they said.'

iii- \n  ----for new line but will have to use print statement for \n to be interpreted

>>>s = 'First line.\nSecond line.'  # \n means newline
'First line.\nSecond line.'

>>>print(s)  # with print(), special characters are interpreted, so \n produces new line
First line.
Second line.

iv- what is raw strings?
>>>print('C:\some\name')  # here \n means newline!
C:\some
ame

>>>print(r'C:\some\name')  # note the r before the quote
C:\some\name

v- strings can be concatenated using +(ONLY STR)
    x='bus'
>>>    x+es
    'buses'
vi- 'py'  'thon' is equal to 'python'
vii-indexing 
    x='answer'
    x[0]='a'
    x[-1]='r'
viii-slicing
    x[:2]='an'

 | P | y | t | h | o | n |
 +---+---+---+---+---+---+
 0   1   2   3   4   5   6
-6  -5  -4  -3  -2  -1

ix-what is index out of range error . name error , syntax error?
x-strings are immutable i.e.
    x[0]=i isnt allowed  (type error)
xi-what is len()?
xii-some imp str methods--
            capitalize(), casefold(), lower(), upper(), replace(), split(), strip(), swapcase(), title()
xiii- what is f strings and .format()?
xiv- there is something print style formating (i dont know it)


5-  LIST
i-they can contain hetrogenous type of data types they are like arrays
 my_list=[1,2,3,4,'a',{'a':1,(1,2,3,)}]
ii- the are mutable and allow indexing and slicing and steping 



























