&nbsp;&nbsp;&nbsp;&nbsp;[home](http://tiny.cc/se17) | 
[syllabus](https://github.com/txt/se17/blob/master/doc/syllabus.md) | 
[submit](http://tiny.cc/se17give) |
[chat](https://se17.slack.com/)  
[<img width=900 src="https://raw.githubusercontent.com/txt/se17/master/img/se17.png">](http://tiny.cc/se17)   <br>
&nbsp;&nbsp;&nbsp;&nbsp;[&copy; 2017](https://github.com/txt/se17/blob/master/LICENSE.md) tim&commat;menzies.us<br>

_______

# Review 2 : Questions 2/14/2017

## Early lifecycle project planning:


1.    What are drawbacks of early requirement addressing?
2.    Define and distinguish unit, integration, system and integration tsting.
3.    Describe two problems of underestimation effort.
4.    Describe two problems of underestimating effort.
5.    Boehm reports a certain shape in the cost-estimation uncertainty curve as a project moves from initial planning to final delivery
    - Draw that shape
     - Why does the  shape change as the development continues?
6. According to Brook's Law, why does adding   more programmers to a late project make taht project later?

## Process planning:

0.    Draw the v-diagram. Divide into 
1.    Spiral models
       - What is the commit partition?
       - How is spriral connected to waterfall?
      - How is the spiral model _different_ to waterfall model?
      - How is the spiral model _the same_ as the waterfall model?
2.    When spiral model should not be practiced? Explain.
3.    Facebook ships many small  changes , very often.
      -  Which kind of s/w strategy method this is? 
4.    What are the phases of Test Driven Development cycle?
      -  List and explain three advantages of Test Driven Development?
      -  List and explain three disadvantages of Test Driven Development?

## Effort estimation

1. What is software overestimation? What are its effects on development?
2. What is software underestimation? What are its effects on development?
3. What is "big bang estimation"? Describe its advantages and disadvantages.
4. How to do run software projects via "feature maturity"?
     - What kinds of organizations are suitable for adopting this strategy?
5. What is parametric software effort estimation?
    - What is needed to use this kind of estimation?
6. Explain each of the following approaches to effort estimation:
     - Big bang?
7. An analysts estimates the development time of a softare project, as a single value. What are the drawbacks to such a single-point estimate?

```python 
_  = None;  Coc2tunings = [[
#              vlow  low   nom   high  vhigh  xhigh   
# scale factors:
'Flex',        5.07, 4.05, 3.04, 2.03, 1.01,     _],[
'Pmat',        7.80, 6.24, 4.68, 3.12, 1.56,     _],[
'Prec',        6.20, 4.96, 3.72, 2.48, 1.24,     _],[
'Resl',        7.07, 5.65, 4.24, 2.83, 1.41,     _],[
'Team',        5.48, 4.38, 3.29, 2.19, 1.01,     _],[

# negative effort multipliers (more means faster)        
'acap',        1.42, 1.19, 1.00, 0.85, 0.71,    _],[
'aexp',        1.22, 1.10, 1.00, 0.88, 0.81,    _],[
'ltex',        1.20, 1.09, 1.00, 0.91, 0.84,    _],[
'pcap',        1.34, 1.15, 1.00, 0.88, 0.76,    _],[ 
'pcon',        1.29, 1.12, 1.00, 0.90, 0.81,    _],[
'plex',        1.19, 1.09, 1.00, 0.91, 0.85,    _],[
'sced',        1.43, 1.14, 1.00, 1.00, 1.00,    _],[ 
'site',        1.22, 1.09, 1.00, 0.93, 0.86, 0.80],[
'tool',        1.17, 1.09, 1.00, 0.90, 0.78,    _],[

# positive effort multipliers (more means slower)
'cplx',        0.73, 0.87, 1.00, 1.17, 1.34, 1.74],[
'data',           _, 0.90, 1.00, 1.14, 1.28,    _],[
'docu',        0.81, 0.91, 1.00, 1.11, 1.23,    _],[
'pvol',           _, 0.87, 1.00, 1.15, 1.30,    _],[
'rely',        0.82, 0.92, 1.00, 1.10, 1.26,    _],[
'ruse',           _, 0.95, 1.00, 1.07, 1.15, 1.24],[ 
'stor',           _,    _, 1.00, 1.05, 1.17, 1.46],[
'time',           _,    _, 1.00, 1.11, 1.29, 1.63]]
```

8.     COCOMO is a parametric effort estimation methods
      - What is the central intuition of the COCOMO equation?
      - Write down the COCOMO equation (hint: it should fit in half a line)
      - What are the for "P" of the COCOMO attributes? Give one example of each "P"
      - In COCOMO co-effecients are shown above, what is `acap` ? What happens to project development effort when it is increased? Why?
      - In COCOMO co-effecients are shown above, what is `cplx` ? What happens to project development effort when it is increased? Why?
      - From the above parameters, find how much faster a fully distributed system compared to a fully
centralized site. If needed, you may assume that the system has 100,000 lines of code.
9.    What is delphi based method? 
       - Why use it instead of COCOMO?
10.    "Planning poker" is  strategy is suitable for group discussion effort estimation environment
      -  Describe this approach plus one advantage and one disadvantage of using this method.
11.    What is no estimate method? When might it be s necessary? 
12.    Case base reasoning is called a non-parametric method.
      - Why? Hint: your answer will have to describe how it works
      - Give  2 advantages and disadvantages of CBR.
      - Given the following project data, what estimate would case-based reasoning assign to the last row? Note that the words
        in t

|analyst capability|multi-site development |use of tools| product complexity| khours(estimate)|
|--|-|-|--|---|
|5   | 1|    5   | 1|    100|
|1   | 5 |   5  |  5 |   800|
|3  |  3  |  3 |   3  |  500|
|2 |   5   | 3|    5   | ?|

## Requirements

![](http://www.isa.us.es/sites/www.isa.us.es.featuremodelanalysis/files/images/MobilePhone.png)

1.   Consider the above feature model of a mobile phone. What features are allowed and forbidden in this diagram?
2.   Consider the design of a car. Every car has a body, transmission, and engine. 
     A car does not necessarily have a trailer. The engine may be powered with gasoline or with electricity or with both. Draw a feature model for car.
2.   A client has asked you to develop a word processor. 
     - Write two non functional requirements for this scenario.
       For each, list factors that make them easier or harder to fill
     - List two functional requirements
       For each, list factors that make them easier or harder to fill

