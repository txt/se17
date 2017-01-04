&nbsp;&nbsp;&nbsp;&nbsp;[home](http://tiny.cc/se17) | 
[syllabus](https://github.com/txt/se17/blob/master/doc/syllabus.md) | 
[submit](http://tiny.cc/se17give) |
[chat](https://se17.slack.com/)  
[<img width=900 src="https://raw.githubusercontent.com/txt/se17/master/img/se17.png">](http://tiny.cc/se17)   <br>
&nbsp;&nbsp;&nbsp;&nbsp;[&copy; 2017](https://github.com/txt/se17/blob/master/LICENSE.md) tim&commat;menzies.us<br>

_______

<img align=right width=500 src="http://se16.unbox.org/_img/girlbot.jpg">

# Project

_"Every feature is an experiment."_   
-- Laurie Williams

_"Sure, you can code. But can you engineer?"_   
-- Tim Menzies

Software Engineering is the:

+ process of the
+ design,
+ construction and
+ maintenance of
+ good enough
+ software,
+ given the available resources.

The last point means that we are always trading off between what
we want with what we need with what we've got. Software engineers,
therefore are the people we look to:

+ Make and
+ justify
+ well-informed decisions
+ about trade-offs
+ in software engineering.

This, in turn means that at any time, software engineering are aware
of multiple possibilities and the reasons why we should be doing
one, and not the others.
 
So, lets check if you are engineers...

In this project you will find a problem,  define and build and assess three different solutions to  that problem. Make a recommendation
which of those three (if any) should actually be used.

|when|what| notes|
|----|----|------|
|Jan31|Find your users     |A community of people who have a problem with X|
|     |Document a  baseline|Document what problems people have with X|
|     |Conduct research    |Look into  how other people have solved X (using software)|
|     |Lightning talk      |short minute briefing (20 slides * 20 seconds each to class on your problem) **must** include notes on your proposed solution|
|Feb28|Propose solutions   |3 different ways to solve X|
|     |Significant progress|Code demos showing the 3 solutions|
|     |Evaluation plan     |Materials required for user eval sessions. Must include answers to [this questionnaire](https://github.com/REU-SOS/HumanStudy/blob/master/testplan.pdf).|
|Mar30|Results             |Document your improvement (if any)i.e. document how people's experience changes with X|
|     |Recommendations     |Make a reasoned recommendation; i.e. write a report that reports your 3 designs, your methods, your results, and your recommendations for which (if any) to use.|
|     | Lightning talk     |10 minute briefing (20 slides * 30 seconds each) to class on your problem)  **must** present your results and recommendations|
|Apr30|Software analytics  |Report on project bad smells (inferred from Gihub activity). For more on this part, see [here](badsmells.md)|

Note that:
- there is no coding in January, 
- no user trials in Feburary or April.
- the April work is very different to Jan, Feb, March

## What to hand in

### Jan 

Give a talk, submit the slides and a 5+ page  report

Note that the Jan report is just a few pages. Takes some work, but an easy first step.

For example, here are some of the reports from last year.

Clipit (better copy paste tools) 
- Extensive analysis of the literature (great) 
- No new data collection (perhaps less than great)
- https://github.com/cleebp/csc-510-group-g/blob/master/feb1/report.pdf

Simple shot (managing screen snaps)
- Extensive user questioning (great). 
- Not really drive by the ltierature (perhaps less than great)
- https://github.com/Arjun-Code-Knight/csc510-se-project/blob/master/SIMPLSHOT_ACM.pdf
 
Expense tracker (managing day to day expenses)
- best balanced approach (literature + user studies)
- Note: they did **not** ask users what they wanted; instead, they **watched** what they did and tracked standard errors
- https://github.com/sandz-in/csc510_group_l/blob/master/feb1/ExpenseSharing.pdf

### Feb 

All you need to submit here are links to some log pages in Github plus a
few pages describing your March evaluation plan.

### March

Give a talk, submit the slides and a 6+ page  report

## How to find a community with a problem with X:

1. Do whatever you want.
2. Or, think about the classes you did last semester. Think about the organization of that subject, the students who tool that subject the content of that subject, who might use the content of that subject in the real world. Would any of those people have particular kinds of problems either in taking that particular subject, or in using the concepts of that subject in the real world? Can you solve those problems? 


## Rules

- Teams are assign randomly. Why?
      - Cause its great to meet new people. 
      - Also,   in industry, you often get teamed with other people. Get used to it!
- Work must be submitted to 	[http://tiny.cc/givese17](http://tiny.cc/givese17)
      - Post unlinks to you pdf reports/talsk
      - Do not post raw links. Rather, use [tiny.cc](http://tiny.cc) to produce a 
        short human-readable URL; e.g. `http://tiny.cc/se17jan` could be group g's
        report for the January deliverable. Also `http://tiny.cc/se17janTalk`
        could be the talk for that deliverable.
- All your work must be in Github. 
       - Everything that someone else would need  to reproduce your work.   
       - Every group needs `timm` and `effat` as members.
- All you reports must be pdf generated from ShareLatex. Can't use Latex? Then time to learn:
 <a href="https://storage.googleapis.com/instapage-user-media/cba104e6/6832348-0-screen2x.png"><img src="https://storage.googleapis.com/instapage-user-media/cba104e6/6832348-0-screen2x.png" align=right width=300></a>
     - All reports must conform to the typographical style of [Latex conference style files
of IEEE](https://www.ieee.org/conferences_events/conferences/publishing/templates.html). 
     - No deviations.
- All your presentations **must** be written in Google slides. No Prezi. No Powerpoint. No raw pdf.
     - All talks must be click at go (in url, set `start=true`)
     - All talks must auto advance each slide every 30 seconds. No more, no less. (in url, set `delayms=30000`)
  

## Red flags

- Not meeting tomorrow
     - Meet for 10 minutes tonight; prime the pumps with some intial idea
     - Meet tomorrow for an hour. Map out January, when you have to do what. Do it.
- Whole team is working on one person's pet project they ahve been nursing along for years
     - Unlikely that person will relinquish control of their baby
- Team explores 3 options, with no guiding principle. 
     - "We don't have a theory."
     - "Can't find anyone who has done anything like this before." 
     - Yeah, right...
- Group breakdown reproted to me with deadlines less than 1 week away
     - The time to fix management issues is BEFORE deadline pressure hits
- Using NCSU github
     - Don't. Use public github
- Using Private repos
     - Dont.     
- Github commits, comments are very rare, only from one person
     - "But we do pair programming, all typing together".
     - Really, all the time? Every day of the week?
- Team members using incompatiable environments
     - Everyone should be able to run everyone else's code
     - e.g. if Python, you want to indent with 2 spaces? 4 spaces? tab? Whatever. Jsut be consistent across the team.
- Team coding right up to the due dates
     - What? No testing phase?
     - And what about all the work that happens after coding?
- Team members do not share any code; 
     - e.g. "we are building 3 seperate systems on Windows, Mac, Android."
- Team members communicate rarely.
- Team members communicate in email or Slack, not Github
     - Makes the last project hard
- Team members never comment on each other issues in Github.
- Wierd reports
    - Reports not written in Latex
    - Reports that are very short (less than 6 pages)
    - Reports with figures not mentioned in text
    - Reports with no bibliograghies
    - Reports written by only 1 person in the project. e.g. "help me, help me, my subject mark is bad cause Tim was writing the report and he
  did a bad job". Nope. Reports are **everyone's** responsbilities
- Team's three different "versions" justs uses 3 different learners.
    - Data miners are only "different" if they offer a different user experience
    - So standard Naive Bayes and Decision tree learners are the "same"
    - But what would be different for suers is showing them the decision trees and saying
  "you landed here, you want to be there, here is the difference in the tree branches".
- Building from scratch
    - Better to eapfrog into your work by reusing some other code base.
    - For example, for anything with user input, consider the Subline Text editor. It has a
  [nifty package manager](https://packagecontrol.io/) that allows you to switch between packagages, even at runtime (makes experimentation easy).	     





