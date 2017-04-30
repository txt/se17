&nbsp;&nbsp;&nbsp;&nbsp;[home](http://tiny.cc/se17) | 
[syllabus](https://github.com/txt/se17/blob/master/doc/syllabus.md) | 
[submit](http://tiny.cc/se17give) |
[chat](https://se17.slack.com/)  
[<img width=900 src="https://raw.githubusercontent.com/txt/se17/master/img/se17.png">](http://tiny.cc/se17)   <br>
&nbsp;&nbsp;&nbsp;&nbsp;[&copy; 2017](https://github.com/txt/se17/blob/master/LICENSE.md) tim&commat;menzies.us<br>

________________
# Review Ques 5

1. As precisely as you can (two lines each, at most), define the following.  Your definition should mention inputs,outputs and side-effects:
    - functions
    - predictes
2. If, in a purely logical language what are the outputs and side-effects of the following:
    - emp(tim,42) = emp(Name,Age)
    - emp(Who,42)  =  emp(tom, Age)
    - emp(tom,42) = emp(tim,Age)
What are logical language? What are predicate and argument in logical language? Give 2 examples
3. Define "closures"? In the following, when the `add` variable is initialized, what are the two parts of it contents?

```
 add = (function () {
    var counter = 0;
    return function () {return counter += 1;}
})();

add();
add();
add();
```
When the above `add` is created, then used 3 times, what is returns?             
    - a nil pointer error? sdfsdffds
// the counter is now 4
```
 
 4.What is type inference?
 5. What is folding?
 6.Erlag: 
  a) Describe uses of Erlang in 2 sectors
  b) Write two properties of Erlang.
7) What is the difference in block structured language compared with functional language variable scope?
Pattern
8)YAGNI rule of 3?
9) Suppose you are working with a 3-tier architecture system for employee management. The system composed of -database layer, business logic, and GUI. Many parts of codes are reused in this system. As an example: you have to insert/update employees age several times. What design pattern is should be implemented in business logic for this application? Give reasoning on behalf of your answer.
10) When a leaf compiles the process? (composite)
