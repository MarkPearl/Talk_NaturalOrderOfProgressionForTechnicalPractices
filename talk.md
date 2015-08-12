## Introduction ##

When I had my thirteenth birthday, my parents bought me a skateboard. This wasn't your ordinary plain shaped skateboard. The deck on this skateboard was what we would call a cruizer deck. It was aerodynamic and was about the coolest thing a thirteen year-old had ever seen. Entering teenhood, and having just been given what I considered an amazing skateboard, I decided that this was my calling in life - I would become world renown for skateboarding abilities.

So, in attempt to reach get fame, I tried to learn some of the tricks I had seen on TV - airs, backsides, kickflips, ollies etc. It turned out, there were a few challenges I was not going to overcome to be able to perform these tricks effectively, namely my coordination or lack there of. 

Having failed at tricks, I came up with a cunning a genious plan - what I lacked in skill, I could make up in speed. I would be known as the world most famous skateboard luge. With this new found hope of achieving my goal, I set out to find an appropriate hill to ride. Having grown up in KwaZulu Natal, in a place called Forest Hills, I was in no shortage of "good" hills. In fact, about a block away from my house was a perfect specimen with a new tarred road going down its steep incline.

I remember this event to this day. It was a late Janruary afternoon, my brothers and I walked to the top of the hill where I stood for a few moments staring down the it as if I was a surfer looking for a large wave to surf. Then, with very little ceremony, I climbed on my skateboard and pushed off. About 10 seconds into the ride and about 5 meters down the hill I had an inclining that I hadn't thought this through properly. My skateboard was doing really well, it was picking up speed quickly, however, there were a few things that I hadn't planned for. Firstly, I had not planned for the what if's like me crashing. I was wearing shorts and a T-Shirt and wasn't wearing any protective gear (in fact I didn't own any). Also, the logistics of what would happen when I reached the bottom of the hill had not been thought through properly. You see, the road I was riding down came to an abrupt stop at the bottom as it joined a T Junction. Cars traveling along the other road at the bottom of the hill had zero visibility of anything coming down the hill which was fine for cars that had breaks, but not so great for a skateboard. As these thoughts dawned on me and my speed rapidly increased I made probably the first good decision that day - I jumped off my skateboard. 

As I jumped off, my world went into slow motion - the skateboard which had just seconds before been under my feet continued on down the hill for a few meters until it veered off and crashed into bushes. I also continued down the road for a few meters - but with no protective gear I had to rely on my bare hands and knees to help me come to a stop. Standing up and looking down at my hands and knees I was surprized that where moments ago there was healthy skin, there was now replaced blood and torn flesh. 

## Relating Skateboarding to Software Development ##

In my professional career of developing software I've seen and heard of many organizations doing exactly the same thing that I did on my skateboard that day. These organizations want to develop software faster - they've figuratively bought the agile skateboard (they've sent everyone on an agile course, put up a scrum board and are doing daily stand ups) and they haven't really thought it through properly - they've missed something really important which is if you want to develop software faster it is naive to think that the only thing you need to adjust is how you interact - you also need to adjust your engineering practices.

How do so many organizations miss something so obvious? Part of the reason is because the two most popular agile methodologies in circulation, Scrum and Kanban, don't specify any specific engineering practices to adopt when applying them - that doesn't mean they advocate bad software engineering practices, they are just not specific on what good engineering practices are. This is a problem. It has left many organizations not realizing that there are additional skills and practices they will need to adopt to be able to engineer software effectively. 

Another problem lies with the software engineers. Software engineers are used to being considered bright, which often makes them blind to areas of improvement. For instance, for the first 10 years of my professional career I thought I was really good - until I started to pair program that I had a long way to go and a lot to learn. 

Today I would like to touch on some of the things that are rarely spoken about at a Scrum or Kanban course and that managers and "non" technical people often don't get to discuss but that are just as critical. I've called them the natural order of agile technical practices.

## What are agile technical practices ##

So, what do I mean by agile technical practices? These words mean different things for different people. This became very apparent when I posed the question on twitter to the general software development community. For the next 25 minutes I'm going to ask your endulgance in using my definition for the term - which is that when I say agile technical practices I am referring to the engineering practices related to creating software in an agile environment. Some of the things I would include under the banner of engineering practices are: Pair Programming, Mob Programming, Continous Integration, Continous Deployment, Acceptance Test Driven Development, Collective Code Ownership, Collective Coding Standards, Simple Design and Refactoring.

## How do you know if you need Agile Technical Practices? ##

Why are these agile technical practices important? Let me illustrate with a story - a few years ago I was involved with my first big project. At the time it was the largest code base I had ever worked on and I was involved with it for about 6 years. Since I wrote the first line and last line of code for it, I have a pretty good feel for it's entire lifespan - the system was called QuoteMaster and it was my get rich quick ticket. The first few months of developing QuoteMaster were exciting. We managed to add a number of key features to the system and our customer were very positive in their feedback. As the months passed by it seemed to take longer and longer to add additional features even though we added more developers to the team. At the time the only way I could explain it was that the code was becoming complex and making a change sometimes created unexpected errors in other places in the system and was making us have to go slowly. After about 4 years into the project we had pretty much come to a standstill. You know something is fundamentally wrong with a system when potentially your largest client asks for a relatively small feature and you point blank refuse to do it because of how long it was going to take and the pain and emotional strain it was going to cause you. In a nutshell, I didn't feel safe anymore making changes to QuoteMaster.

Sadly, the story of QuoteMaster is not unique. I have been involved in several QuoteMaster like applications and I am pretty sure many of you are currently involved in QuoteMaster projects. The practices I am going to talk about today are what I consider critical to help you stop making more QuoteMasters. They are the figurative safety gear you need to wear to ride the agile skateboard. They will help give you the confidence and ability to speed up with time instead of slowing down.

## Structure, Interactions & Technical Practices are Intertwined ##

With that, I want to briefly mention team and organizational structures. There is a great talk Kent Beck did at Lean Kanban Scotland called Gforce where he spoke about how team structure and speed are linked. The practices I am going to talk about today are designed primarily for teams that want a fast release rate. In Kent's talk he makes the statement that different rates of release require different team and organizational structures. Today I'm going to assume you have your team and organizational strutures sorted. I know that is not necessarily true for all of you so if you are unsure whether your team structure is appropriate I recommend watching Kent's talk.

Gauging how big a jump in speed you are going to make will also give you a good indication of how many new engineering practices your team will need to adopt. This is important because whenever you adopt a new engineering practice you will see a dip in performance while the new practice is being learned and applied. If you include too many practices at once you make the dip in performance to deep and the recovery period to long.

To avoid this, you want to start with practices that are easy to apply in your current structure. Then, as you seeing the benefits of those practices prepare your team and organization for the next step. 

So, with that said, let's look at some of the technical practices a team releasing per quarter should adopt. 

----------------------------------------------------------------------------------------------------

## Quarterly Release ##

I've been in a few environments where software was being released quarterly. Looking back at these environments, it was never just one team involved. To get a release to occur on a quarterly cycle usually involved several teams - at least a dev team, a test team and sometimes an ops team. The workflow which was most common was as follows - the dev team would do a bunch of work, as they neared end of quarter they would hand the work over to the test team to validate and discover bugs after a few back and forths the release would be declared as ready and handed over to the ops team to deploy. For the next few weeks after the go-live date you would consistently worry that you had missed something or that you were going to get a call in the middle of the night to come and fix a bug that was not picked up.

If I looked closer at these dev teams and how they would split work up, it was usually in functional silos. Each developer would be an expert in a specific part of the code base with barely anyone else every looking at another persons code. 

Because releases were done infrequently, one person in the dev team usually became the release guru spending days if not weeks at an end of a quarter to get a release package put together. 

So, what are the practices that teams in this situation should have in place before trying to move up a gear?


### Common Code Contract ###

For me a common team coding standard means that it should be hard to recognize the individual that coded a specific section. To achieve this, the people writing code need to talk often. To start this off I have found it useful for teams to have a frequent touch base on what their approach is when solving a problem. Since people are still usually working predominantly on their own, variations will occur, and when these crop up it is important that the team keep discussing and trying to reach consensus.

### Version Control System ###

Part of a base requirement for making a build server is a version control system. If you are not using a version control system right now, stop what you are doing and do it. I recommend distributed version control systems with a preference for Git - if you don't want to use git that's fine, but use a version control system.

A quick side note, I once was working with a team that was trying to increase their release cadence. One of the first questions I asked was are you using version control to which they responded yes. It wasn't until a few days into working with them that I discovered they had their solution under version control, and if you looked in the version controlled reponsitory they had several sub folders eached named after members in the team with an exact copy of the entire solution. Version control is not just backup of code - one of the major advantages of version control is resolving merge conflicts. This is one of the biggest advantages of using version control.
### Automated Builds ###

Democratizing and automating the build means that anyone in the team should be able to create a build or release package. Most teams will tell you this is going to be very hard and that they have special circumstances that require a specific person owning the build. Personally, I have yet to come across a team that hasn't been able to share this responsibility across the team after applying their minds and doing enough research. A major benefit of automating the build is that it removes some stress between developers and testers. There is nothing more depressing than being told by a tester that they have picked up a minor bug, and that you now have to spend a few days making a new release.


----------------------------------------------------------------------------------------------------

## Monthly Release Cycle ##

The teams I've work with that release on a monthly cadence were co-located cross functional teams consisting of at least a combination of developers and testers. 

### Developer Testing ###

One of the practices that was necessary to adopt to succesfully get to a monthly cadence was developer testing. Developer testing turns out to be a extremely useful practice and yet something fairly challenging to learn. 

Often I hear people who have not done developer testing before get confussed on terminology - most often I hear people speak about needing to do TDD, and on further discussion they are actually referring more generally to developer testing . Developer testing includes test driven development, unit testing, regression testing, acceptance testing, integration testing as well as a bunch of other 'testing' practices. For those unfamiliar with these terms, these tests are not written by the people who hold the title 'tester' - they are written by developers.

I remember when I first heard of developer testing I was at a Microsoft Dev Day. I saw someone put some code up on the screen, click a button and a bunch circles on the screen went green. I thought, great, finally the silver bullet to software development. All I needed to do was go home and write tests and then I wouldn't have any bugs. So, I went home, spent a very frustrating day or two trying to write a useful test against the system I was developing at that time. I failed, I could not write a single useful test - it turns out the code I had written was not testable - so I gave up and reverted back to my normal coding. 

Which part of developer testing you start with depends on your unique problem. Personally, I tried to start with small unit tests and do TDD but struggled. I ended up writing larger integration tests first, then coming back to smaller unit tests later. It wasn't until I attended a Code Retreat that I really began to get into Developer Testing. My recomendation is, if you are in an organization that wants to parctice developer testing but don't know where to start, Code Retreats are a good introduction.

The challenge a team faces when it wants to reliably release on a monthly cadence is that developer testing is vital for success. If a team does not adopt certain forms of developer testing they create too much to much of a workload for manual testing - which makes everyone hate the world. 

Looking back at my personal career - If I could redo developer testing, I wished I understood basic refactoring tests first. These are automated tests that typically are slow but give you some level of confidence that that you haven't broken anything major. I think for most systems this is a useful place to start as most developers come in to an existing system.

### Collective Code Ownership ###

At the same time, collective code ownership becomes necessary. When on a quarterly cadence you can group work into silos but when you move to a monthly cadence you might not have work for certain silos. You see a few effects from this, firstly pieces of work taken on by individuals gets smaller, and it is not feasible for people to only work in their own area. This means opening the code base up to the team and allowing people to work in areas they would not have previously touched. 

### Build Server ###

Doing smaller bit of work suddenly highlights what a headache it is to integrate code. This is where a build server really pays of. A build server, also called a continous integration server, is a centralized server that builds your project whenever a checkin is done by a developer on the team to version control - it's responsbility is to build the code base in version control, making sure that everything is there and working nicely. Once it has a successful build, it then runs the automated developer tests to make sure they are passing.


### Collaborative Coding ###

I have found the best way to get collective code ownership is through collaborative coding. These are the four stages of collaborative coding I have gone through. I love talking about this, if you are intersted in sharing your experiences feel free to chat to me after this session.

----------------------------------------------------------------------------------------------------

## Weekly Release Cycle ##

Personally I have found that getting from a monthly to a weekly release cadence was substantially easier than getting from a quarterly to a monthly release cadence.You already have a solid base for success and most of the tools to get there.

### One Button Deploy ###

The one big technical practice that we had to polish up when moving to a weekly deployment was a one button deployment. One button deployment means literally that, you click a button and the latest passing build is moved into your production enviroment - while this can be done with scripting and a buildserver, I recommend using tools specifically designed for this.

#### Advanced Developer Testing #####

To get to a one button deployment, we found that we had to re-look at Developer and Manual Testing - some things are extremely hard to test with just developer testing and so some form of manual testing needs to be performed, however looking at what is being manually tested and making that as easy to test as possible has some really big payoffs. These types of tests are often not trivial and require some effort. I was in a team recently that was experiencing this pain, they had a combination of developer and manual tests. Spending some time with the testers to understand what they were covering manually and where their pain points were made it possible to streamline the process without introducing any holes in our safety net. This allowed us to get down to a weekly release cadence and eventually a daily release cadence.

## Daily Deployments ##

Moving from a weekly to a daily deployment is largely psychological. A time that I was part of had been releasing to production reguarly once a week. For an extended period some of the people in the team wanted to move to a daily release, yet there seemed to always be a good reason to delay the deployment to once a week.

Eventually, there was enough desire to move to a daily deployment. I remember the first week we deployed to product every day. There was very little to speak about in the daily stand up and there seemed to be a psychological break through. It was also interesting having a conversation with a user, and then the next day doing the work and making it immediately available to them to use.

----------------------------------------------------------------------------------------------------

So,

- some practices return minimum value unless coupled with other practices
- practices need to be sustainable during pressure situations (teams without these practices are often in pressure situaitons a lot)

------------------------------------- END -------------------------------------

With that said, I know that every team is a unique snow flake. I understand that what I will be sharing might not map one to one with your teams exact situation. I would love to find out the specifics of the pain you are facing afterwards.

Essentially when I am developing software I want feedback at every level. The quicker the feedback the better. I want feedback when I am solving a problem to know if it is the right problem to solve. I want feedback when I am coding to know if my approach is right. I want feedback when I release to know if everything is working properly. The quicker I can get this feedback, the better position I am in.



For those that are unfamiliar with the term, collective code ownership means that everyone is responsible for all the code. This in return means that everyone is allowed to change any part of the code. I have sometime seen people confusing version control with collective code ownership. Just because your team has their code in version control does not mean there is collective code ownership - I have seen teams have a large solution, where inside that solution they had a folder for each developer, under which they had a copy of the code. This is not collective ownership. 


Good to know
- Every practice has a J curve - can you afford to have the downtime
- Some practices return minimum value unless coupled with other practices
- Should be able to sustain practices during pressure situationo
- Legacy system testing

Other things
- Manual testing slows things down
- Learn your refactoring tools

What are agile engineering rpactices
- TDD,
- Pairing,
- Continous Integration
- Continous Deployment
- Acceptance Test Driven Developement

When it is expensive to make something, you do it less frequently. When it is cheap, you do it more often

At a principle level what we are looking for is... any practice that helps shorten feedback loops and promote sustainable pace.

## Definition ##

Engineering Practice is a specific software development practice that is proposed to be implemented by agile method.


Many think Agile is just about stand-ups & sticky notes when it is actually about being able to deliver valuable software faster. It is impossible to do this if you don't leverage the technical practices agile has embraced. The challenge is - where do you start? Do you focus your energy on understanding TDD, or put time into a continuous build environment. What is the natural order of progression and how do you implement them without slowing down feature delivery?

In this session Mark is going to present what he believes is the natural order of progression of technical practices. He will highlight some of the challenges he's faced with teams trying to increase their release rate and what they did to overcome these barriers.

This talk is appropriate for technical AND non-technical people involved in Software Development who would like to release to production more frequently (be it from Months to Weeks, Weeks to Days, or Days to Hours). Those already hitting the magical continuous release rate don't need to attend ;-)
## How is your topic relevant to an African context ##

## Keywords ##

TDD, 
Automated Deployment, 
Continuous Integration, 
Version Control, 
Automated Testing, 
Deliver Faster

## Learning Outcomes ##
Understand the order of implementing technical practices
Understand why each technical practice is valuable
Understand how long each technical practice usually takes to embrace or see a return on
Debunk potential myths on why one technical practice will solve all your problems

References - Agile Engineering Practices (http://blogs.versionone.com/agile_management/2013/07/10/agile-engineering-practices-a-cheat-sheet/)  

Potential Engineering Practices
- Pair Programming
- Test Driven Design
- Automated Acceptance Testing
- Refactoring
- Emergent Design
- Continuous Integration
- Shared code repository

References - Agile Egineering Best Practices - http://www.slideshare.net/RichardChengExcella/agile-engineering-best-practices-what-every-project-manager-should-know?next_slideshow=1

Do this first...
- Version control
- Build automation
- Automated unit testing
- Continous integration
- Static code analysis
- Dependency Management
- Automated integration testing
- Automated acceptance testing
- Deployment automation

References - Benefit of agile engineering practices - http://www.infoq.com/articles/benefit-agile-engineering

https://blog.codecentric.de/en/2014/05/agile-engineering-practices-short-overview/

Videos on egile engineering practices
http://shop.oreilly.com/product/0636920020271.do

Why did we lose the XP practices (https://coding.abel.nu/2014/04/why-did-we-lose-the-xp-practices/)

https://www.scrumalliance.org/community/articles/2010/december/the-land-that-scrum-forgot

Uncle bob's idea of engineering practices include:
- TDD, Continuous Integration, Pair Programming, Collective Ownership & Refactoring

Uncle bob feels TDD is the best to start with - it helps make the code clean

## My Quotes ##

If you want to move faster without getting hurt, the people that are creating your software not only need to adjust how they interact - they also need to adjust their engineering practices that they use that makes it safe to move faster. 


My advice is aim for small speed improvements. If you were previously at a month release cycle, aim for a quarterly release cycle, then to a monthly, then to a bi-weekly, etc.

(When you change a team structure, you end up changing the organizational structures. Organizational stuctures tend to be self supporting - unless they have been properly prepared for change they will treat the change as a virus that needs to be quarenteened and removed.


When a person adopts any new engineering practice the J Curve effect happens which in essence says that their productivity will dip for a while before it improves. If you adopt too many practices at once, you introduce a massive jcurve, which is often unfeasuble.


. Teams that don't have slack do not have capacity to change. Having slack built in as a regular cadence into your process is vital for continued improvement. I'm a proponent of teams doing intential improvement on at worst a weekly cadence.


To counter the JCurve you need slack.  When I talk about slack I'm not referring to [SLACK], I am refering to the time a team has to improving their process and upskilling. Having slack is vital to adopting new practices. Without slack you will not be able to adopt new practices, which means you are not going to be able to speed up. I word of advice when creating slack - prefer small regular intervals of learning. I have found teams that have small daily and weekly sessions to improve and learn are a lot more effective than teams that take a week or a month to "upskill". 
 
