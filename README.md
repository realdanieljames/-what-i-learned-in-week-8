# -what-i-learned-in-week-8


## For - of loop

- **EXAMPLE 1**
```
const array1 = ['a', 'b', 'c'];

for (const element of array1) {
  console.log(element);
}

    // expected output: "a"
    // expected output: "b"
    // expected output: "c"
```


- **EXAMPLE 2**
```
const iterable = [10, 20, 30];

for (let value of iterable) {
  value += 1;
  console.log(value);
}
    // 11
    // 21
    // 31
```



### Syntax
``` 
    for (variable of iterable{
        statement
    }
```
for each value in variable


## function Expressions

# Working with arrays 
<hr>  


## MAP  

- mapping through an array, pushes to a new array [], transforming each value from the original array [], into a new value into the new array [].
<hr>

## FILTER

- filtering through an array chooses what value in the original array will be copied into the new array, leaving the unwanted values in the original array []


<hr>




## Week 8's Introduction to FUN new METHODS 
.startsWith()  
.includes()  
Math.random()  
Math.floor()  
.indexOf()  
- returns the index number of specified value
- return '-1' if specified value was found

process.argv  
- **-  the built-in array that node populates with our user arguments.**
- always starts at index 2 
- give me an input , i'll give it right back to you.
- cuts out all the white spaces when console logging a sentence that contains spaces.


.join()  
