# Learning Python

## 4. More Control Flow Tools
1- if statement 
i-they are conditinal statements followed by elif and else
ii- if :
    means checking for true 
iii-match()- the statement matching only gets exceuted.
    
    def http_error(status):
    match status:
        case 400:
            return "Bad request"
        case 404:
            return "Not found"
        case 418:
            return "I'm a teapot"
        case _:
            return "Something's wrong with the internet"


2- for statement
i- to iterate over items of any sequence that gives an edge over other language (in python we can iterate over str,list,dict etc.)
ii-range() is a generator that generates AP
iii-sum()- to sum a list etc,
    
    break()-to get out of existing loop
    
    continue()-it continues the loop even if condition is satisfied. 
    for num in range(2, 10):
        if num % 2 == 0:
            print("Found an even number", num)
            continue

3- while()-like for loop 
    i=0
    while i<=5:
        do this 
        i+=1
4-  pass- does nothing 
5-  function()- 
    def(a,b):
        do something
        return x
i-what is args**(arguments) ans kwargs**(keyword arguments)?
ii-what is lambda ?
    is anonymous function, when we want to write a func for temp basis
    x=lambda a:a*2
iii-documentation strings- when we want to perform multiline comment to define a module or a func



