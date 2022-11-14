# Code reading

## Question 1

Take a look at the following code:

```
1    let x = 1;
2    function f1()
3    {
4        let x = 2;
5        console.log(x);
6    }
7    console.log(x);
```
Because the first variable in the function body  is local and the second one is global..
Explain why line 4 and line 6 output different numbers.

## Question 2

Take a look at the following code:

```
let x = 10

function f1()
{
    console.log(x)
    let y = 20
}

console.log(f1())
console.log(y)
```

What will be the output of this code. Explain your answer in 50 words or less.
The output will the vlaue of x, for the first console.log and for the second one will be undefined.

## Question 3

Take a look at the following code:

```
const x = 9;

function f1(val) {
  val = val + 1;
  return val;
}

f1(x); It will call the function
console.log(x); It will print 9

const y = { x: 9 };

function f2(val) {
  val.x = val.x + 1;
  return val;
}

f2(y); we will call the function
console.log(y); it will print {x:10}
```

What will be the output of this code. Explain your answer in 50 words or less.
