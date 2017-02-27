&nbsp;&nbsp;&nbsp;&nbsp;[home](http://tiny.cc/se17) | 
[syllabus](https://github.com/txt/se17/blob/master/doc/syllabus.md) | 
[submit](http://tiny.cc/se17give) |
[chat](https://se17.slack.com/)  
[<img width=900 src="https://raw.githubusercontent.com/txt/se17/master/img/se17.png">](http://tiny.cc/se17)   <br>
&nbsp;&nbsp;&nbsp;&nbsp;[&copy; 2017](https://github.com/txt/se17/blob/master/LICENSE.md) tim&commat;menzies.us<br>

________________
# Review Ques 3 02/14/2017

## Requirement Analysis:

- Defend the following statements
      - Before building any software, it is wise to spend much time collecting details requirements docs.
      - Requirements engineering is a waste of time
- What is commit partition? What is commit partition strategy in spiral model?
- Defend the following statemetns
      - Reuse is the key to productivity
      - Reuse is dangerous 
- What are the arguments for and against pushing small codes to review?
______________________________________________
 
## Visual Notations for Programming:
 
- Write two advantages of state chart. 
- When state chart is not recommended?
- Draw a state chart for the following states and transitions:

```
struct transition state_transitions [] = {
{entry, ok, foo},
{entry, fail, end},
{foo, ok, bar},
{foo, fail, end},
{foo, repeat, foo},
{bar, ok, end},
{bar, fail, end},
{bar, repeat, foo}};
```  

- Write three differences between SQL and No-SQL.
- Suppose you have three tables in database: University, Subject and Student. What are insert, update and delete anomalies in this context?
- How ER based model solves different anomalies for the above scenario? Explain.
- Why doe some people claim ER is not suitable for agile development?
-  What state chart and ER based models have in common?
- What is compartmental model? Give a small example of using this model for a grocery shop supply chain from warehouse to supermarket shelves.
- What are the limitations of compartmental model?
