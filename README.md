# RacketProject


##  Professor - Dr IAN McLOUGHLIN


#### GNumber - G00305450

#### The project is made for as a part of college work , Module  THEORY OF ALGORITHMS.

#### CountDown number game where user can give program some random numbers and target number and program have to figure out target number by using (+ - * / ) operators .

#### Here is small example of it in action .  In this instance, one number was selected from the large set, and the rest from the small set.

Contestants must use the four basic operations, With the six random numbers to calculate the target number. They don’t have to use all six of the numbers, however each of the six random numbers can only be used once, If the same number appears twice in the list of six then it may be used twice. At each intermediate step of the calculation, negative numbers and fractions are not allowed. For example - we can’t subtract a 7 from a 2, as that would give -5, and likewise you can’t divide 2 by 7 as that gives a fraction.

```
     [ +  -   *   /  ]
```

```
  { 50 , 8 , 3 , 7 , 2 , 10 }
  
  The randomly selected target was 556.
  
  There are multiple ways to solve this. The smallest solution requires just four numbers:
  
  (8 7 * 50 10 * +) = 556 (Through Reverse Polish Notation)
  
  
```

## Reverse Polish Notation

![](https://github.com/sarabDevOps/RacketProject/blob/main/rpn.JPG)

 Reverse Polish notation (RPN) is a method for representing expressions in which the operator symbol is placed after the arguments being operated on. Polish notation, in which the operator comes before the operands, was invented in the 1920s by the Polish mathematician Jan Lucasiewicz. In the late 1950s, Australian philosopher and computer scientist Charles L. Hamblin suggested placing the operator after the operands and hence created reverse polish notation.

For example, the following RPN expression will produce the sum of 2 and 3, namely 5: 2 3 +.

Reverse Polish notation, also known as postfix notation, contrasts with the "infix notation" of standard arithmetic expressions in which the operator symbol appears between the operands.

RPN has the property that brackets are not required to represent the order of evaluation or grouping of the terms. RPN expressions are simply evaluated from left to right and this greatly simplifies the computation of the expression within computer programs. As an example, the arithmetic expression (3+4)×5 can be expressed in RPN as 3 4 + 5 ×.

In practice RPN can be conveniently evaluated using a stack structure. Reading the expression from left to right, the following operations are performed:

1. If a value appears next in the expression, push this value on to the stack.

2. If an operator appears next, pop two items from the top of the stack and push the result of the operation on to the stack.

A standard infix arithmetic expression can be converted to an RPN expression using a parsing algorithm as a recursive descent parse.

RPN is used in Hewlett Packard and some Texas Instruments calculators and internally in some computer languages. 

for more info [Click Me ](https://en.wikipedia.org/wiki/Reverse_Polish_notation)

## Racket Language

Racket is a general purpose,multi-paradigm programming language in the Lisp-Scheme family. One of its design goals is to serve as a platform for language creation, design, and implementation. The language is used in a variety of contexts such as scripting, general-purpose programming, Computer Science.

Functional programming is a pervasive technique in Racket.

Functional programming means designing our program around self-contained functions that don’t rely on state or mutation.

In functional programming, everything the function needs to do its job is passed as an input argument, and the function provides its result as a return value, which replaces the previous value.

A benefit of functional programming is that it makes functions easier to test. It also promotes com­pos­abil­ity, which is the idea of combining simple, self-contained functions to produce more elaborate behavior.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

Download and extract the zip folder here [Racket-Project](https://github.com/sarabDevOps/RacketProject/archive/master.zip)

## Prerequisites

Dr Racket. You can download here [Dr Racket](https://download.racket-lang.org/)


## Installing

Once you have downloaded the executable file click on it and it will automatic guide you for installation.

Or here is the video tutorial how to install [DR Racket](https://www.youtube.com/watch?v=UOqcLGGKVr8) on your machine. 






## Deployment

File menu from DrRacket ----> Hit the open ------>  select.rkt file from file Explorer 


## Built With

* [Racket](https://download.racket-lang.org/) - Racket 



## Versioning

Version 1


## Authors

[SarabDevOps](https://github.com/sarabDevOps)


## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/sarabDevOps/RacketProject/blob/main/LICENSE) file for details








 
