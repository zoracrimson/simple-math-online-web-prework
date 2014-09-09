---
tags: readme
language: ruby
resources: 0
track: web development
topic: ruby
unit: hello world
lesson: simple math
---

# Math

Ruby can perform any operation that a simple calculator can. Open up IRB (open your terminal then type `irb` and hit enter) then type the commands below:

* 1 + 1
* 1 * 3
* sqrt(81)
* 9 ** 2

Programs have basic arithmetic built-in. The `+`, `*`, and `/` methods are part of Ruby. Type `9 / 2`. The result is probably unexpected. This is because Ruby has types. When you call the `/` method on Integers, they return integers. Instead, type `9.0 / 2.0`. Numbers with decimals in Ruby are called Floats and when you divide Floats, the `/` method returns floats.

Enclosing an expression in () defines an order of operation.

* 98 +59872/13*8*-51
* 98 + (59872 / (13*8)) * -51
