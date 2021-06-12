## Pre-Work Reading Notes
[Home](https://tjohnson986.github.io/reading-notes/)

#### Table of Contents
1. Reading - Solving Prolems
1. Reading - Act Like You Make $1000/hr
1. Reading - How to Think Like A Programmer
1. Reading - The 5 Whys
1. Video - What the Heck is an Event Loop Anyway
1. Video - The Super Mario Effect


### Solving Problems
[Original Article](https://simpleprogrammer.com/solving-problems-breaking-it-down/)

#### Common Mistakes during an interview - Trying to write code as soon as possible
- Trying to over solve the solution on the first try

#### Steps to solve any algorithm type problem
1. Read the problem entirely twice
1. Solve the problem manually with 3 sets of sample data
1. Optimize the manual steps
1. Write manual steps as comments
1. Replace comments with real code
1. Optimize real code


### Act Like You Make $1000/hr
[Original Article](https://medium.com/swlh/pretend-your-time-is-worth-1-000-hour-and-youll-become-100x-more-productive-f04628bb3e6d)

Busyness is actually a bad thing, since it shows a lack of focus and the ability to say no to several other competing tasks. 

Busyness and stress are the enemy. Busyness could be a distraction from what really matters. It's a sign that you're off track, lazy and undisciplined.

Deep work - not tolerating any distractions and producing quality and quantity in a short time. If you don't manage your time, it will manage you. 

Ask you think, so you are. If you assign yourself a low value, others will treat you as a low value. But if you know your time is valuable and present that, people with recognize and respect it. You attract what you look for. 


### How To Think Like A Programmer
[Original Article](https://www.freecodecamp.org/news/how-to-think-like-a-programmer-lessons-in-problem-solving-d1d8bf1de7d2/)

Problem solving skills are almost always prioritized over other skills and the most important qualification that employers look for.

When encountering a new problem follow these steps: 
1. **Understand** - Most problems are hard because you don't understand them. Know exactly what is being asked. Explain the problem, write it down or sketch it out to unlock things you haven't seen.

2. **Plan** - Don't start solving the prolem without a plan. Nothing can help you if you cannot write down the exact steps.

3. **Divide** - Don't try to solve one big problem, but rather break it into sub-problems that are easier to solve. Then solve each one by one. Begin with the easiest. Once you've solved each sub problem, connect them. 

4. **Stuck?** - Debug, Reassess, Research

**Practice!** 


### The 5 Whys
[Original Article](https://www.mindtools.com/pages/article/newTMC_5W.htm)

Developed by Toyota Industries founder Sakichi Toyoda, the 5 Whys technique is simply when a problem occurs, drill down to the root cause by asking "Why?" 5 times. When a counter measure becomes apparent, you follow it to prevent the issue from happening again. 

#### How to use the 5 Whys: 
1. **Assemble a Team** - gather together those who are familiar with the specifics and process.
1. **Define the Problem** - Observe the problem if possible and write a clear problem statement.
1. **Ask the first "Why"** - Search for answers grounded in fact, of what actually happened, not guesses at what might have happened.
1. **Ask "Why?" Four More times** - using answers from first why, ask further Whys in order and move quickly to avoid jumping to conclusions.
1. **Know When To Stop** - When asking why produces no more useful responses, an appropriate counter-measure or process change should become evident.
- Tip 1 - The "5" in 5 Whys is a rule of thumb, it may take more
- Tip 2 - Someone may have failed to take a necessary action. This allows to ask why it happened rather than assigning blame and lead to process improvements.
1. **Address the Root Cause(s)** - When one root cause is identified, discuss and agree on counter-measure that will prevent it from happening again.
1. **Monitor Your Measures** - Watch how counter-measures eliminate or minimize initial problem, amend or replace if necessary.


### What the Heck is an Event Loop Anyway 
[Original Video](https://www.youtube.com/watch?v=8aGhZQkoFbQ)

The Event Loop has a very simple job. It looks at the stack and looks at the task queue. If the stack is empty, it pushes any tasks in the queue to the stack.

setTimeout 0 will immediately queue the task in the queue, which will then run when the queue is empty.

Utlizing the task queue can free up the stack and allow other code to run. Otherwise, the stack is held up by the open task until it is finished.


### Super Mario Effect
[Original Video](https://www.youtube.com/watch?v=9vJRopau0g0)

This talk illustrates the need to keep a growth perspective. To know you'll fail to learn, and not to focus on the failures but rather how to learn from them.

