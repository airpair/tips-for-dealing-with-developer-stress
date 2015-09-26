Synopsis
> This article identifies several types of stress that developers face on a daily basis and explains how they may impact effectiveness. We’ll cover tips for identifying the root cause of the stress and offer suggestions on how to manage them.

## Background
I'm co-authoring this article with Erik Gillespie.<sup>http://technicalrex.com/</sup><sup>https://www.airpair.com/stackoverflow/posts/30-days-of-answers-on-stack-overflow</sup> We have worked on many projects together including fun side projects, business idea pitches, and epic enterprise apps. We've encountered a lot of stressful scenarios ranging from enterprise architectural decisions to where to get lunch (while the latter is mostly intended as a joke, there is a type of stress called “decision fatigue” that contributes to not being able to choose something as routine as lunch – stay tuned to learn more!). We've tried a lot of techniques to overcome these daily stresses and have selected a handful we feel have been most helpful.

As software engineers, our jobs tend to be very stressful.  At its core, our job is to build - and build quickly. But how do you continue to build quickly when stress is getting you down?

How do we keep our throughput as high as possible when:

- Project managers want to add more content
- Accounting wants to cut costs
- Customers have conflicting requirements
- Developers want to try out the latest and greatest everything

We recommend starting with the “5 Whys”.

### The 5 Whys
The “5 Whys” is a strategy to help you identify the source of your stress. Oftentimes when we are stressed, we’re so focused on our current emotions that it is difficult to see the real cause of our troubles.

The 5 Whys<sup>https://en.wikipedia.org/wiki/5_Whys</sup> is a great way to get to the root of all sorts of problems. You start by stating your initial feelings or assessment of a problem and then go through a recursive process of asking yourself "Why?" five times. In many cases you can get a much clearer picture of an underlying problem using this technique.

Let's apply the 5 Whys to a common work scenario:


**Me:** Work was terrible today.<br>
*Why was it terrible?*<br>
**Me:** I had to stay late.<br>
*Why did you have to stay late?*<br>
**Me:** I didn't finish the code changes that I said would be ready for testing tomorrow.<br>
*Why didn't you finish the code changes?*<br>
**Me:** I had five different hour-long meetings today that ate up most of my time.<br>
*Why wasn't 3 hours enough?*<br>
**Me:** It would have been, but I only ever had 15 minutes between meetings to do any work.<br>
*Why did you only have 15 minutes between meetings?*<br>
**Me:** The meetings ran long. Then after catching up on email and remembering what I was working on I barely had time to do anything before my next meeting.


This final answer illustrates one example of four common types of work stress. In an attempt to identify which type of stress you may be looking at, you can ask:

- Does the problem revolve around being undecided about choices in front of you?
- Is it a disagreement with someone you work with?
- Does it make you feel like you're unnecessarily busy, always bouncing between tasks, or forever behind in your work?
- Is it something that you simply don't enjoy doing, is boring, or isn't putting your time to good use?

Let’s dig deeper and put names to these four demons, while we also check out some tips for overcoming them.

## Types of Stress
### Decision Fatigue
Developers have to make dozens of choices, both small and large, every day. These can range from setting up a new product's tech stack to naming a function. All of these small little actions take time and mental energy. They eventually wear on your brain's ability to make decisions, leading to burnout. This stress further cripples your ability to make decisions, and you can get caught in a downward spiral of decision fatigue. How can we overcome this particular stress? 

#### Reduce Options
Consider this comic from *xkcd* <sup>http://xkcd.com/1445/</sup><br>
<img src="https://imgs.xkcd.com/comics/efficiency.png"/>

In many cases this chart is an exaggeration, but consider what happens when you add a Strategy C to the Time Cost. You have to compare Strategy C to both Strategy A and Strategy B. If you consider a Strategy D then you have to compare it to the three previous strategies. Clearly, comparing a large number of strategies is not a winning strategy.

Consequently, our first tip is to reduce the number of options or variables you are considering in your decision-making process. For each option you eliminate, you save yourself the effort of comparing that option to each of the remaining options.

For example, perhaps you want to introduce a JavaScript Templating framework into your application. A quick search might show that there four major contenders. If you can quickly rule out even one of them (perhaps the one option no one on your team has even heard of), then you will save yourself the time and brainpower of comparing it to three other libraries.

#### Decide By Doing
Additionally, making prototypes can be a great tool to reduce the number of available options. It's very easy for an implementation debate to go off on a tangent for hours.  Get to a solution faster by making a simple prototype or demo to actually try something instead of basing decisions on hypotheticals.

You can read all the documentation and blog posts out there, but sometimes simply spending 30 minutes on a building a demo is enough to qualify something as either good or bad.  When working on the prototype, don’t worry about code quality; set a time limit and see how much you can get done. Once you've hit the end of the time limit, do a “gut check”. Were you able to gauge if the idea is going to work, or did you uncover things that would render it inefficient or impractical? If you did open a can of worms, use those results to determine what needs to be improved and pivot to your next option.

### Disagreements
A second major source of stress is disagreement. Most developers don’t work alone.  There are weeks where we spend more time with our coworkers than with our families.  This constant interaction may result (intentionally or not) in reduced professionalism. This and other factors result in disagreements. Some tips for overcoming this stress include:

#### Pick Your Battles
It's easy to find yourself arguing semantics.  Does it really matter if the function is called 'getUserId' or 'getUserID'? Probably not. But too often, people become wrapped up in these tiny details (there's a term for this too: bikeshedding<sup>https://en.wikipedia.org/wiki/Parkinson%27s_law_of_triviality</sup>!).  The discussion becomes counter-productive and time gets more wasted than college kids on St. Patrick’s Day. Even if your idea or choice is more correct, it won't always win. Make peace with it. Sometimes you have to cut your losses in order to keep going.

#### Put it to a Vote
Seriously, show some love for democracy. We've all been in meetings that go in circles while we search for the optimal solution.  Set a time limit and once you've hit it, put the solutions to vote, majority rules. Have a tie? See the next tip.

#### Get a Mediator
Find a neutral party.  It doesn't necessarily have to be an expert or even a developer.  Find someone you can explain the options to in five minutes and get their feedback.  Their new perspective might even make the solution obvious. Sometimes simply stating the problem out loud is enough to help you come to a decision or solution.

### Overloaded
Working nights and weekends? This third stress is a bummer. Check out these savvy solutions to save your personal life from the black hole of time that work can sometimes be.

#### Prioritize
You likely have to deal with two sets of priorities: customer-level priorities (given to you by business-side coworkers) and work that you can actually prioritize. If you feel you’re spending too much time on features that don't deliver enough value to warrant the effort, talk to your project or development manager. Invited to constant meetings? Assess meeting attendees carefully: could someone on your team with your expertise go to the meeting and report back?

Minimize context switching: try and wrap up a task before jumping to others. This will help you knock tasks off your list and off your brain so you can focus on the next project. Get creative about it too: consider compressing all of your meetings to a single day each week, encouraging "No Meeting Mondays," or rescheduling your daily meetings so that they are back-to-back. 

Keep a tight eye on your week: if you’re working extra hours for many consecutive days, you risk burnout, which results in inferior work. Be sure to take time to rest and regenerate; knowing deadlines can help you decide what MUST be done, and what could wait until the next day. 

#### Know Before You Go
A developer should never be caught by surprise by the expectations of the workplace they’ve chosen. Have the foresight to ask those questions during the interview phase and make sure that expectations match up to the work-life balance you want to have. 

### Feeling Stagnant/Bored
There will be times in your career when you won't always get to work on what you enjoy most. That's the job part of it. These tips will help you power through those phases: 

#### Get Involved
Look at this problem from a career perspective: we chose software development because we love it right? Often enough, the most enjoyable aspect of my career is something I'm doing for fun, not money. Writing a tech blog, attending/presenting at a meetup, or coding a fun side project is a great way to get involved with something new. Mixing fun extracurricular items in with the dull makes those dull tasks more tolerable.  You might even get the opportunity to incorporate something new in at work.

## Going Forward
Regardless of what the problem is, you are not the first person to have it. Do your due diligence and try to figure it out, but don't bang your head on the keyboard all day. Talk to another developer or your manager to get help! No one likes a workplace martyr (“look how hard I’m trying to find a solution on my own!”) – do your best to find a solution, but call in for help when too much time is passing.

Now that we've covered some common developers challenges, remember to step back and try to tackle the cause of a problem.  We covered some tips that have worked for us, but if you have a tip that helps you manage stress and focus on producitivity, be sure to let us know in the comments!