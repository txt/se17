&nbsp;&nbsp;&nbsp;&nbsp;[home](http://tiny.cc/se17) | 
[syllabus](https://github.com/txt/se17/blob/master/doc/syllabus.md) | 
[submit](http://tiny.cc/se17give) |
[chat](https://se17.slack.com/)  
[<img width=900 src="https://raw.githubusercontent.com/txt/se17/master/img/se17.png">](http://tiny.cc/se17)   <br>
&nbsp;&nbsp;&nbsp;&nbsp;[&copy; 2017](https://github.com/txt/se17/blob/master/LICENSE.md) tim&commat;menzies.us<br>

_______

# Lecture1

Before we get down to SE theory, our first
lectures will explore the tools and techniques
needed for Project1 (due end of January).

So here is a pretty messy collection of notes and tips on various tools.
Some of this we will work through in class, some you'll need to read for yourself.

____

## Research

### Finding Choice (TM)

Exercise1:

- Problem: "Make it easier to track day to day expenses"
- Think, pair, share:
     - 2 minutes. Dream of options
     - 5 minites: pair with your neighbor, share ideas, try to find better ones
     - 8 minutes: around the room "what are our best ideas?"

Exercise2:
 
- Problem: "how to find a car park"
- Go to Google scholar and see what you can find

### Reading the literature (TM)

Dancing through the years with google scholar

- Case study "problems with parking"

Places to search for papers:

- [IEEE Xplore](http://ieeexplore.ieee.org/Xplore/home.jsp)
- [ACM Portal](http://dl.acm.org/results.cfm?query=software%20engineering&filtered=&within=owners%2Eowner%3DHOSTED&dte=&bfr=&srt=publicationDate)
- [Google Scholar](https://scholar.google.com/scholar?as_ylo=2013&q=software+engineering&hl=en&as_sdt=0,34)

Note that these search engines have "cited by" fields so if you find a good paper, you can run forward in the literature looking for subsequent studies.

Pruning rules (heuristic, take with a grain of salt):

- Recent better than past
- Highly cited better than not

Methodology:

- To grab an initial set of documents, what were your search terms? How many documents did it match (hint: usually 100s to 1000s)
- To prune the intial set , what were your strategies (extra search terms? quick scans of abstracts? number of citation counts? restrictions by year?)
- After pruning, how many docs did you have (hint, usually dozens)?
- How did you study the pruned docs (e.g. what particular questions did you ask of each document? how did you collate the results)?
- What sanity checks were applied?
         - Did the literature review find known key articles in the field
         - Potentially, is it possible to operationalize fixed to the identified problems? e.g. lack of domain knowledge very hard to operationalize; not closing matching brackets (easier to operationalize). Recall the Royce results: 22% of their problems were deep semantic while the result were simple logic and syntax problems.

(R.C. Bryce, A. Cooley, A. Hansen, N. Hayrapetyan,
[A one year empirical study of student programming bugs](http://dx.doi.org/10.1109/FIE.2010.5673143) in Frontiers in Education Conference (FIE), 2010. )

____

## Github (EF)

<iframe width="560" height="315" src="https://www.youtube.com/embed/0fKg7e37bQE" frameborder="0" allowfullscreen></iframe>

### Create an Organziation in Github

One organization has many repositories.


### Github Isses and Labels

Github issues: [tutorial](https://guides.github.com/features/issues/)
and [A simple styleguide for tagging Github issues](https://robinpowered.com/blog/best-practice-system-for-organizing-and-tagging-github-issues/).


### Using master and branches

Newbie GH:

- everyone commits to master. nothing fancy
- FYI- I commit several times a day
- probably suffices for your small class projects

But if you want to see how the gurus do things:
   - [see here](https://guides.github.com/introduction/flow/)
   - [or here](http://scottchacon.com/2011/08/31/github-flow.html) 


_____

## Data Collection Tools

### Googleforms (TM)

See https://support.google.com/docs/answer/87809?hl=en

<iframe width="560" height="315" src="https://www.youtube.com/embed/cm3KyqbaMJA" frameborder="0" allowfullscreen></iframe>

### Mechanical Turk (Jack)

[Introduction to crowd sourcing](https://docs.google.com/presentation/d/1B5Z8Ohf6xRdhLM6q49_z0PUjAHY15w9Pt3o8yADix8I/edit#slide=id.gc6f75fceb_0_5)


### Talking to people

Good news:

- To evaluate your software, you have been given access to
  a group of 65&times; 10 / 20 = 32 people you can use  a 1 hour eval session. 
      - Which you can use for your January and March work when you ahve to evaluate software
      - So, in theory, groups of 16 people

Bad news:

- That group is.... you. To earn 10  marks for this subject, you will have to volunteer for 5 &times; 1 hour eval sessions in Jan and March
- Scheduling nightmare. It'll be... messy. Realistically, getting groups of 5 to 10 to comment on your software in Jan/Mar will
  be more achiveable.

In any case, once you've got those people, what can you do with them?

[A wide range of options](https://github.com/REU-SOS/HumanStudy/blob/master/handout.pdf).
You will most probably use or or more of:

1. Semi-structured or structured interviews
2. Questionaire
3. Focus groups
4. Think aloud
5. a analysis methods 

Exercise 3: Think-pair-share

- Rank each of the above 5 points, plus GoogleGorms and Mechanical Turk, in terms of cost and effectiveness in gaining insight on software
     - 2 minutes. Dream of options
     - 5 minites: pair with your neighbor, share ideas, try to find better ones
     - 8 minutes: around the room "what are our best ideas?"

### Polcies with People Data 

No matter what is done, all sessions must start with

- Identifying who you are (some contact details passed to subject)
- A gift. Muffins. Coffee. Pizza. Something to make them feel wanted.
- Explanation of what we are doing
- Stress the user's rights
       - The right not to participate (they can leave, now, if they want to)
       - The right to privacy (user identifiers will NEVER be stored with data)
       - The right to be forgotten (on request, you WILL delete this user's data)

After that, you could...

- Run sample exercise 1 (done by experimenters)
- Run structured exercise 2 (what the user does, perhaps with a thinking 
- Conduct structured debrief (e.g. ask them to fill in a questionniare)
- Do something unstructured (e.g. ask them to think aloud, reflect; here you
  are looking for 

_____

## Reporting (TM)

### Pecha Kucha

20 slides, 20-30 secs each slide. For example: http://tiny.cc/timm7.

Go to slides.google.com

- Write some slides (20, max).
      - Be kind. Add page number and short URLs to all slides
      - Always have a “for more info” slide
- File > Publish to web
-  Edit link. 
       - Set `start=true`   (auto start's slides)
       - Set `delayms=30000` (30 secs per slide)

```
https://docs.google.com/presentation/d/1GgwBtcyni0VXvm9PLzx3oQl8C4_lcdKNK8T2SWTohQI/pub?start=true&loop=false&delayms=20000&slide=id.p
 ```

[Pecha Kucha: Tips, Resources & Examples](http://cmmr.usc.edu//Pecha_Kucha_TipsResourcesExamples.pdf)

### Latex (EF)

<a href="https://storage.googleapis.com/instapage-user-media/cba104e6/6832348-0-screen2x.png"><img width=400
align=right src="https://storage.googleapis.com/instapage-user-media/cba104e6/6832348-0-screen2x.png"></a>

Sharelatex

- http://sharelatex.com
- Remember:  push the big blue button.
- Link the sharelatex project to a repo in your organization
- at least one member of each group has to get the "collaborator" plan (normally $15/month, student plans for $8/month)
      - Can link to Github
      - can create a share project and invite others.
- the rest can live in free "Personal" land

Bibtex

Adding figures (btw, NOT excel graphics)

You probably won't need this, but for completenesss.

- [Not-so-short-introduction to Latex](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwj8qPuuxKjRAhVENSYKHdFCCugQFggaMAA&url=https%3A%2F%2Ftobi.oetiker.ch%2Flshort%2Flshort.pdf&usg=AFQjCNFBLNe8MyAG11nkWmIuM5lfQap4bA&sig2=QZM1s-veuj0Ob14ct_nuAQ&bvm=bv.142059868,d.eWE)
