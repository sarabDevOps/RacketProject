# RacketProject


##  Professor - Dr IAN McLOUGHLIN


#### GNumber - G00305450

#### The project is made for as a part of college work , Module  THEORY OF ALGORITHMS.

#### CountDown number game where user can give program some random numbers and target number and program have to figure out target number by using (+ - * / ) operators .

#### Here is small example of it in action .  In this instance, one number was selected from the large set, and the rest from the small set.

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

Version 7.3 [May 2019](https://download.racket-lang.org/)


## Authors

[SarabDevOps](https://github.com/sarabDevOps)


## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/sarbjeetkumar/Racket-Project/blob/master/LICENSE) file for details








 
