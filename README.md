# Math

## Objectives

1. Practice doing basic math in Ruby
2. Understand how division in Ruby differs from normal division
3. Understand the modulo operator
4. Understand the Math module
5. Create appropriate behavior for methods

## Introduction

Programs have basic arithmetic built-in. The `+`, `*`, and `/` methods are part of Ruby.

Ruby can perform any operation that a simple calculator can. Open up IRB (open your terminal then type `irb` and hit enter) then type the commands below:

* `1 + 1`
* `1 * 3`
* `Math.sqrt(81)`
* `9 ** 2`

## Order of Operations

Enclosing an expression in parentheses `()` defines an order of operations, like you would [expect](http://en.wikipedia.org/wiki/Order_of_operations).

* `98 + 59/13 * 8 * -5 = -62` 
* `98 + (59/(13*8)) * -5 = 98`

## Division and Intro to Floats

Type `9 / 2`. You would expect the result to be 4.5, but it's actually 4. This is because of the type of number you are using. In Ruby, and most programming languages, numbers can be integers (whole numbers), or floats(decimal numbers). When you divide  integers, they return integers without rounding. The decimal is just removed. If you type 9.0, you're creating a float, so  `9.0 / 2.0 = 4.5`. Numbers with decimals are called floats and when you divide floats a float is returned. If you divide a float and an integer, a float will be returned, so `9.0/2 = 4.5`.

## Modulo operator

There is another operator that is really useful in programming. It's the modulo, and is represented with the percent sign `%`. The modulo operator gives you the remainder of a number divided by another number. So `5 % 3 = 2`.

## Practice

Now open `lib/math.rb`. You'll find a bunch of empty methods that take numbers as arguments that the methods will use to perform the mathematical operations on. Get the tests passing.
