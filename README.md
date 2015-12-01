# awesome-repl

%%%

### Ruby Repl

Anything goes here.  Write a method that takes any string argument and returns an array containing that arg 3 times.

~~~ruby

# Code your solution here

~~~solution

def jonas_loop(str)
  arr = []
  3.times { arr << str }
end


jonas_loop("hi")

~~~validation

assert.isArray(response);
assert.equal(response.length, 3);

~~~

%%%

<a href='https://learn.co/lessons/awesome-repl' data-visibility='hidden'>Learn.co resource</a>
