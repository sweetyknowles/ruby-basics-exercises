### Assorted Data Types

#### What are the outputs and/or side effects of the following code snippets? "Error out" is a valid answer choice. Make a guess before testing your answer.

```rb
2 ** 3
```
```text
Your answer.
```

```rb
((16 / 4) * (2 + 1)) ** 2
```
```text
Your answer.
```

```rb
("a milli " + "a milli") * 3
```
```text
Your answer.
```

```rb
("a milli " * 4) / 2
```
```text
Your answer.
```

### Truthiness and Falsiness

#### Which of these evaluate as `false` in Ruby? Mark all that apply.

```text
[ ] false
[ ] 0
[ ] ""
[ ] null
[ ] undefined
[ ] NaN
[ ] nil
```

#### What are the outputs and/or side effects of the following code snippets? "Error out" is a valid answer choice. Make a guess before testing your answer.

```rb
name = gets.chomp
if name
  puts "My name is: " + name
end
```
```text
Your answer.
```

```rb
no_name = ""
if name
  puts "My name is: " + name
end
```
```text
Your answer.
```

```rb
no_name = nil
if name
  puts "My name is: " + name
end
```
```text
Your answer.
```

### Conditionals

#### Write FizzBuzz in Ruby!

Fizz-Buzz is a classic coding exercise that you can create using your knowledge of conditionals and loops. Implement code that does the following...

* Counts from 1 to 100 and prints out something for each number.
* If the number is divisible by 3, print `"Fizz"`.
* If the number is divisible by 5, print `"Buzz"`.
* If the number is divisible by both 3 and 5, print `"FizzBuzz"`.
* If the number does not meet any of the above conditions, just print the number.

Your output should look something like this...
```
1, 2, Fizz, 4, Buzz, Fizz, 7, 8, Fizz, Buzz, 11, Fizz, 13, 14, Fizz Buzz, 16, 17, Fizz, 19, Buzz, Fizz, 22, 23, Fizz, Buzz, 26, Fizz, 28, 29, Fizz Buzz, 31, 32, Fizz, 34, Buzz, Fizz, ...
```

You technically haven't learned Ruby loops yet, so we got you started with one below (although you should be able to make sense of it). All you have to do is change the content of the loop.

```rb
i = 0
while i <= 100
  # Your code goes in here.
end
```
