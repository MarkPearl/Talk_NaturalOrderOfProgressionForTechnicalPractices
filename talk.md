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

Why are these practices important? Let me illustrate with a story - a few years ago I was involved with my first big project. At the time it was the largest code base I had ever worked on and I was involved with it for about 6 years. Since I wrote the first line and last line of code for it, I have a pretty good feel for it's entire lifespan - the system was called QuoteMaster and it was my get rich quick ticket. The first few months of developing QuoteMaster were exciting. We managed to add a number of key features to the system and our customers were very positive in their feedback. As the months passed by it seemed to take longer and longer to add additional features even though we added more developers to the team. At the time the only way I could explain it was that the code was becoming complex and making a change sometimes created unexpected errors in other places in the system. After about 4 years into the project we had pretty much come to a standstill. You know something is fundamentally wrong with a system when your potentially largest client asks for a relatively small feature and you point blank refuse to do it because of how long it was going to take and the pain and emotional strain it was going to cause you. In a nutshell, I didn't feel safe anymore making changes to QuoteMaster.

Sadly, the story of QuoteMaster is not unique. I have been involved in several QuoteMaster like applications and I am pretty sure many of you are currently involved in QuoteMaster projects. The reason why the practices I am going to talk about today are important is because they are critical to help you stop making more QuoteMasters. They are the figurative safety gear you need to wear when riding the agile skateboard. They will help give you the confidence and ability to speed up with time instead of slowing down. 

## Structure, Interactions & Technical Practices are Intertwined ##

With that, I want to briefly mention team and organizational structures. There is a really good talk Kent Beck did at Lean Kanban Scotland a few years back called Gforce where he spoke about how team structure and speed are linked. In Kent's talk he made the statement that different rates of release require different team and organizational structures. Today I'm going to assume you have your team and organizational strutures sorted - for some of you this is not necessarily the case. Technical practices and team structures are also linked. Some practices may be impossible to get off the ground if you don't have a suitable team structure. If you are unsure whether your team structure is suitable I recommend watching Kent's talk.

## Dips & Slack ##

So, what can you as a manager or someone with influence do to help your team learn and adopt new practices? Firstly, you need to create slack and weather the dips.

When I talk about slack, I am refering to the time a team has to improving their process and upskilling. Without slack your teams will not be able to adopt new practices, which means things won't get better. As a manager, a good rule of thumb is to prefer small regular intervals of slack over large infrequent blocks. I have found that teams that have small daily and weekly sessions built into their routine learn and improve at a noticably faster rate than teams that take a week or a month at a time. 

 Also, whenever a team or an individual or team learns a new engineering practice there is going to be an initial dip in performance. You need to be in a position to support them during the dip. You need to have enough understanding of the long term advantges that will be gained from what they are learning to be their advocate to the rest of the organization during the dip. 

Avoid attempting too many new practices at once. If you include too many practices at once you make the dip deeper and the recovery period longer. In the worst case, it could even mean that a team abandons all of these practices as "none of it works" when they're overwhelmed by all of these changes at once. 

I'm sometimes told that its not a good time, that an organization can't afford to create slack because the project is at a critical point. While this may sometimes be true, my observation is that in most situations projects are always at a critical point and it's never a good time. If you are in an organization that suffers from this, you need to realize that things are never going to get better than they are now and you either need to come to terms with this, or change your organization. My advice is be an advocate for slack being part of the day to day process. 

So how do you create slack? One way is to invest in practices that have a shallow dip and a quick recovery period. These practices may not necessarily be the most valuable practices in the long run, but may be necessary to create the additional slack needed to embark on the harder and sometimes more beneficial practices. 

The pattern I like to use is as follows: Identify where your bottlenecks are. Have an understanding of what practices can help reduce those bottlenecks and roughly how expensive the practices are to adopt by your team. Let the team pick an appropriate practice, let them learn and apply it to their system, as the practice starts to realize a return they will have created additional capacity. Let your team re-invest the additional capacity to create additional slack to apply to the next identified bottleneck. Rinse and repeat several times. At some point you will create more time than you need for sustainable slack. When this happens your team becomes progressively faster. And the intersting thing with getting progressively faster is that it becomes a drug. The faster you go, the faster you want to go.

So, with that said, let's move on to some actual practices.

----------------------------------------------------------------------------------------------------

## Automating and Democratizing the Build ##

I've put this as the first practice to look at because this is a low hanging fruit, yet I have come across many teams that don't do it. When I refer to the build I am talking about the set of files that are packaged or generated that are required to for a system to run on a test or production environment. For teams that previously released infrequently, this is usually a manual process owned by a single person. When you automate the build it means that instead of someone manually going through the steps to create a build, it is done automatically by a script file. Democratizing the build means anyone in the team should be able to trigger this process - even the non-technical people. 

How do you know if your build is automated? A good way to guage is to ask a team to generate a build - if it takes them more than a minute or two, it is not automated enough.

Most teams I have come across that have not automated the build yet will tell me it is going to be very hard and that they have special circumstances that require a specific person owning the build and doing it manually. Personally, I have yet to come across a team that hasn't been able to share this responsibility across the team after applying their minds and doing enough research. 

I once worked with a team that was under a huge amount of pressure working on a very legacy application. There was one particular developer that stood out as always being busy. After some time with the team we noticed that every couple of weeks this particular developer would disapear for a day to make a build for the testers. Because of the pressure he was under, occaisonally he would miss a step during the build process and send through build pack with an old file. This would only get picked up after a few hours of it being with the testers which meant he would then need to spend another day re-doing the build and the manual testing would need start over gain. You can imagine how popular he was when this happened and how much he enjoyed his build days. 

After quite a bit of encouragement we convinced him to give us time to help him automate the build. It took us a day or two, but we managed to fully automate the build. What once was an error prone process took almost a full day of a developers time was reduced to a matter of seconds. 

We didn't just automate the build. We had just created an additional a day and a half of extra time a month for a very over worked developer. Automation made making a build painless, this resulted in the team making smaller more frequent builds which resulted in more frequent releases which business got features a lot sooner than they had previously. If you have not automated and democratized the build, stop what your team is doing and invest the time in it now.

----------------------------------------------------------------------------------------------------

### Version Control System ###

Leading on from builds is the practice of using version control. Version control is not just backup of code - one of the major advantages of version control is resolving merge conflicts. This means that many developers can work simultaneously on the same code base and the version control system will do the majority of the work involved in putting their code together as a single solution. 

I've seen version control frequently misused, abused or totally ignored by teams. One of the most common symptoms of misuse is when teams complain of frequent merge conflicts. This is a symptom of the team not continuously integrating. Continous integration starts with a discipline, everyone needs to continuously integrate to trunk.  If your team has murmurings of their version control system not working or how they hate it you are going to be dead in the water trying to get more advanced technical practices implemented. Make it a priority to get any pain in your version control resolved.

To be successful with version control do small little bits of work and integrate frequently (and by frequently I am meaning hours, not days).

----------------------------------------------------------------------------------------------------

### Continous Integration Server ###

Doing smaller bits of work and integrating more frequently means that people work closer together. It becomes vital to make build and integration issues visible as quickly as possible - this is where a continous integration server comes into play. 

A CI Server, also called a build server, is a centralized server that builds your project whenever a checkin is done by a developer on the team to the version control - it's responsbility is to build the code base from version control, making sure that everything is there and working nicely. Once it has a successful build, it can do other things like run automated tests etc. 

One of the big payoffs from a ci server is that it can make the general health of your codebase visible to everyone regardless of whether you are technical or not - For instance, in a couple of teams that I have been involved with we plugged a monitor into our ci server that we put up in the team room. Whenever a developer commited work to version control, our ci server would automatically detect it, rebuild the solution and tell everyone how the build went. It used 3 colors - orange meant it was currently building, green meant that the last build was a success, and red meant we had broken something. Our team goal was try and keep the ci server green all the time. 

Making the ci server physically visible to the entire team helped us focus on sorting out integrations issues quickly and allowed everyone to keep it in the back of their mind. 

Setting up a ci server is extremely low hanging fruit provided you have a spare server, automated build scripts and your version control system working.

----------------------------------------------------------------------------------------------------

### Collective Code Ownership ###

So, let's say you have your build scripts humming, your version control working smoothly and your ci server continously integrating. What else can you get value from? I would like to talk a bit about the pratices that support the principle of collective code ownership.

Why does collective code ownership matter to you? For one of my clients the principle mattered because a developer went rogue and held the organization to ransom because he was the only person who understood a mission critical system. For another client collective code ownership is important because they have seen reduced bottlenecks in developing software because more people can work on a wider area of the system. At an engineering level, I have found this principle supports better design, better flow and in general makes daily work fun. 

So what is it? Collective code ownership is the principle that code belongs to the project, not the individual. There are several practices one can apply to realize this principle.

#### Common Code Style ####

One practice falling under collective code ownership is having a team having a common coding style. By this I don't mean a thick document outlining exactly how everything is done and dictated by the architects in the architect forum - that doesn't work. I rather mean a team having a common understanding on how they would solve certain problems and what coding style and standard is important to them. Parts of a common coding style may be valuable to document, but definately not all of it. A common code style is the first step to collective code ownership.

#### Collaborative Coding ####

So how do you know if your team has has a common style. One of the outcomes of collective code ownership is that it should be hard to identify which individual in your team coded a specific part of the system. To achieve this, the people writing code need to talk often. How do you get this to happen? I have found the best way to achieve this is to support collaborative coding. There are several different types of collaborative coding. On the diagram I have put up, the further right you go the more collaborative you become.

Now, typically when I talk about collaborative coding someone will ask how can one justify the costs of two or more people doing one persons job? In fact, just the other day my beautiful wife asked me this exact question.

The best way I can explain why these forms of programming work is by explaining what we mean when we say that someone is programming. Programming is not about typing, it's about problem solving. Depending on the problem being solved, there are many advantages to having more than one person working together on it. When we talk about pair programming or mob programming we are in effect doing group problem solving. 

Working together on the same problem at the same time is the best way I have found to get a common code style and adopt collective code ownership. One of the big complaints I have with most of corporate South Africa is that we are not making our work environments condusive to this type of work. I am not a fan of cubicles, designed to do factory line work. I want to see places where it is comfortable for a group of people to sit together and see eachother screens, or move around.

If you are in a position to make decisions on a work environment, investing real money into making the facilities at your office conducive to collaborative development is money well spent.

----------------------------------------------------------------------------------------------------

### Test Driven Development ###

So, you have created a collaborative environment, the people are working well together, where do you go from here? There are a number of practices you can consider, as the last practice I'm going to talk about today, I thought I would speak about automated testing and test driven development.

In several discussions I've had with people who have not practiced any form of test driven development before, I find they get confused between test driven development and automated tests in general. There are some significant differences.

Test driven development or TDD is a particular workflow that developers use when writing software.  It involves first the developer writing an automated test that defines a desired improvement or new function, the developer then produces the minimum amount of code to get the test to pass and finally refactors the new code to acceptable standards.

The benefits of TDD include helping create a simple design and inspiring confidence in a developer that the code is doing what it is meant to be doing. 

Automated tests on the other hand are merely that, a set of tests that can be run automatically and written by anyone at any point in time to verify that a system is functioning as expected. Some automated tests can be written post development by testers. These types of tests merely verify that the system is operating as expected and yield no benefits to design.

TDD is extremely useful to learn. Firstly it teaches developers good design - for instance how to write software that is loosely coupled. What do I mean by things being loosely coupled? The best analogy I can think of is this : If programming features was like building blocks, then pre-tdd I was making really big blocks and using super glue to keeps the blocks together in the shape I wanted. Learning TDD taught me to make my blocks a lot smaller and them slightly so that they worked like lego blocks - now, instead of having to glue things together I could just clip things in and out rapidly.

Now let me warn you upfront, if you haven't done TDD before, it can be challenging at first to learn. In particular I have seen people try and learn TDD straight out the bat with legacy systems. This can be extremely hard to do.

The first time I saw test driven development I saw someone demonstrate it by writing some code, click a button, and a bunch circles on the screen went green. It looked really simple. I thought, great, all I need to do is go home and write tests and then I wont have any bugs. So, I went home, spent a very frustrating day or two trying to write a useful test against the existing system I was developing. I failed, I could not write a single useful test let alone write it first - the code I had written was not unit testable. So I went back to my normal approach and put the idea on the shelf for a while.

It took me more than a year of occaisonally dabbling with TDD to understand how to do it, and another year to start practicing it but once I began to into it, I began to realize how useful it was.

What is the best way to learn TDD? For me it was attending a thing called a code retreat. I learnt more about TDD in one day at a code retreat than I learnt in an entire year on my own. If you can, I would highly recommend you get your developers to attend a code retreat. There are public code retreats held on weekends a few times a year. Sometimes its challenging to get people with busy lives to attend events on their weekends. If people in your team are in this position I would recommend spending the money getting someone to come and host internal code retreat.

----------------------------------------------------------------------------------------------------

### Closing ###

With that I'm going to end off with a story about a recent project I was involved in - I call this my hope project - it's about a program called MaxCut. MaxCut is a program I have been involved in developing for several years. All it does is show wood and metal workers the best way to cut their material so that they have the least wasteage. The first version was written many years ago before I was introduced to any of the practices I've spoken about today. 

In the early days of MaxCut we noticed the same effects we had seen in QuoteMaster - as we added feature on feature, it was taking longer and longer to make changes and keep everything working together. 

One day I got feature request from a user asking for an adjustment to be made a part of the program - at the time it looked like a really useful feature but I knew that part of the code base was very tricky and it was going to be several weeks if not a month or two to write and then a week to make an installer update. Since we didn't have that sort of time, I parked the feature request and put it in the "Nice Ideas but not going to happen" section.

A year later I exposed to many of the practices I've spoken about today. In particular, two of the things that made a big impression on me were ci servers and test driven development. With time we started refactoring MaxCut and applying these practices on the system. After a while I came across the feature request I had shelved years earlier because of the effort involved to implement it. It just so happened to be a Saturday morning and I had some free time. I wondered how much effort it would take me to attempt that feature now. I sat down, start working on it, by late morning I had completed the feature, had run a full set of tests over the system and was ready to make an installer available. 

The hope is this, what once would have taken weeks, if not months, and would have left me uncertain if I had gotten it right could now be done in hours with a high degree of confidence that I hadn't broken anything. That to me is the power agile technical practices. They make us go faster with time, not slower.

With that I would like to thank you for your time. 

------------------------------------- END -------------------------------------

- some practices return minimum value unless coupled with other practices
- practices need to be sustainable during pressure situations (teams without these practices are often in pressure situaitons a lot)

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


 
