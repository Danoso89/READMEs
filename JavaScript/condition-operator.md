#The condition operator

#What is it?

The ternary operator-also called the condition operator- allows us to return different values depending on the results of checks.
It is an alternative to if...else statement, which can be shorter and clearer, in some cases.

###Example:
```javascript

var test= condition ? expr1 : expr2 


```

Looks better than    

```javascript

if (condition===true) {test=expr1} 
else {test=expr2}

```

doesn't it ? 

In this case, we check for the condition called "condition". If it is true, then the var test is equal to expr1. Else, it is equal to expr2.

###Example 2:

```javascript

return  condition===true ? "condition check result is true" : "condition check result is false" 


```

In this case, we return the first string if the check of condition returns true, otherwise we return the second string. 
       
       
It's an awesome tool that'll add readability to your code. Special thanks to warrior @GiacomoSorbi which posted a kata about it on the gitter channel ;)

###Related:

[Kata:Training JS #7: if..else and ternary operator](http://www.codewars.com/kata/57202aefe8d6c514300001fd)   

[MDN Page](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator)