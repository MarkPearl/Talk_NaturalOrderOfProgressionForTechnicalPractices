## Introduction ##

When I had my thirteenth birthday, my parents bought me an awesome gift, they bought me a skateboard. Now, this wasn't your ordinary plain shaped skateboard. The deck on this board was what is called a cruiser deck. It's one of the coolest things you will ever see. Having just entered teen hood, and being inspired by this board, I realized my calling in life was to become a world famous skate boarder.

To start off, I tried my hand at skateboard tricks - airs, backsides, kick flips, ollies, you name it - what I discovered was that there is one thing common with all skateboard tricks - they require coordination - something that I didn't have. 

Having failed at tricks, I moved on to plan B - I decided what I lacked in coordination, I would make up in speed. With this brilliant idea, I set out with my two younger brothers to find an appropriate hill to demonstrate my ability. 

Having grown up in KwaZulu Natal, in a place called Forest Hills, I was in no shortage of options. In fact, just a block away from where we lived was a perfect specimen of a hill with a newly tarred road going down it.

To this day, I remember the event clearly. It was a late January afternoon, my brothers and I walked to the top of the hill where I stood for a few moments staring down it as if I was a surfer looking at a large wave. Then, with nerves of steel, I climbed on my skateboard and started my descent. 

About 10 seconds into the ride and about 5 meters down the hill I suddenly had a feeling that this might not be a good idea. While my skateboard was doing really well and rapidly picking up speed, it occurred to me that there were a few things I hadn't considered. 

Firstly, the road down this hill came to an abrupt stop at the bottom as it joined a T Junction. Cars traveling along the bottom of the hill had zero visibility of anything coming down it. This was fine for cars that had breaks, but not so great for a skateboard. 

Secondly, and probably more importantly, I wasn't dressed for the occasion. I was wearing shorts and a T-Shirt with no protective gear. 

As these thoughts dawned on me and my speed rapidly increased I made the first good decision of that day - I jumped off. 

As I jumped off, my world went into slow motion - the skateboard which just seconds before had been under my feet continued down the hill and then veered off and crashed into bushes. 

I also continued down the hill for a few meters - but with no protective gear I had to rely on my bare hands and knees to come to a stop. Standing up and looking down I was surprized that where moments ago was healthy skin, was now replaced by blood and torn flesh. 

## Relating Skateboarding to Software Development ##

In my professional career of developing software I've seen and heard of many organizations doing exactly the same thing that I did on my skateboard that day. 

These organizations want to develop software faster - they've sent everyone on an agile course, put up a scrum board and are doing daily stand ups AND they haven't really thought it through properly - they've missed something really important which is if you want to develop software faster it is naive to think that the only thing you need to adjust is how you interact - you also need to adjust your engineering practices.

How do so many organizations miss something so obvious? Part of the reason is because the two most popular agile methodologies in circulation, Scrum and Kanban, don't specify any specific engineering practices to adopt when applying them. That doesn't mean they advocate bad software engineering practices - they are just not specific on what good engineering practices are. 

This is a problem. It has left many organizations not realizing that there are additional skills and practices they will need to adopt to be able to engineer software effectively. 

Today I'm going to speak about some of the things that are rarely spoken about at a Scrum or Kanban course. These are the things that managers and "non" technical people often don't get to discuss but that are just as critical to understand to be effective. 

I've called them the natural order of agile technical practices.

## What are agile technical practices ##

So, what do I mean by agile technical practices? These words mean different things for different people. When I posed this question to someone involved in developing I get a range of answers. 

For the next 25 minutes I'm going to ask your indulgence in using my definition for the term - which is that when I say agile technical practices I am referring to the engineering practices related to creating software in an agile environment. 

Some of the things I would include under the banner of engineering practices are: Collaborative Coding, Continuous Integration, Continuous Deployment, Automated Acceptance Tests, Test Driven Development, Collective Coding Standards, Simple Design and Refactoring.

## How do you know if you need Agile Technical Practices? ##

### Experience of QuoteMaster ###

Why are these practices important? Let me illustrate with an experience - early on in my career I started my first big project - it was a system we named QuoteMaster. I wrote the first lines of code in QuoteMaster in 2001 and 4 years later I wrote the last line of code for it. 

The first few months of developing QuoteMaster we rapidly added features. But as the months passed I noticed something rather alarming. It was taking us longer and longer to add new features. The best way I could explain it was that complexity had crept in and even though we added more developers to the project, it got slower and slower to add things. After about 4 years in, we had pretty much come to a standstill. 

You know something is fundamentally wrong with a system when your largest client asks for a relatively small feature and you point blank refuse to do it because of how long it is going to take and the pain and emotional strain it was going to cause you. 

In a nutshell, we had reached the point where we didn't feel safe making any more changes to QuoteMaster.

Sadly, this experience is not unique. I have been involved in several QuoteMaster like applications and if I were a betting man, many of you here are currently involved in QuoteMaster like projects. 

The reason why the practices I am going to talk about today are important is because they are critical to help you stop making more QuoteMasters. They are the figurative safety gear you need to wear when riding the agile skateboard. They will make you feel safe and give you the confidence to speed up with time instead of slowing down. 

## Structure, Interactions & Technical Practices are intertwined ##

With that, I want to briefly mention team and organizational structures. There is a really good talk Kent Beck did at Lean Kanban Central Europe a few years back called GeForce. In Kent's talk he spoke about how different rates of deployment require structures and activities. 

Today I'm going to assume you have your team and organizational structures sorted - I'm going to assume that you have gotten past the beurocracy of functional silo teams and have small cross functional teams.

It's my observation that engineering practices and team structures are inter-linked. Some practices are impossible to do effectively if you don't have a suitable team structure. If you are unsure whether your team structure is suitable I recommend watching Kent's talk.

## Dips & Slack ##

### Help Create Slack ###

Now, before I speak about the actual engineering practices I want to speak about something that is important for good engineering practices to happen - it’s the necessity of having slack. One of the most important things you can do to help your teams is help them create slack.

When I talk about slack, I am referring to the time a team has to improving their engineering process and upskilling. 

Without slack your teams will not be able to adopt new practices, which mean things won't get better. 

A good rule of thumb to follow with regards to slack is to "prefer small regular intervals of slack over large infrequent blocks of slack". 

I have found that teams that have small daily and weekly sessions built into their normal routine learn and improve at a faster rate than teams that take a large block of time off to learn something new. 

### Supporting the Dips ###

Another thing you need to do is support the dips. Whenever a team or an individual learns a new engineering practice there is going to be an initial dip in performance. 

You need to know that this will happen and have enough understanding of the long term advantages that will be gained from what they are learning and trying to apply to support them during the dips. 

### Pattern to Create Slack ###

So this may all sound great in theory, but in the real world we can't just tell people to stop working. We have deadlines! 

Firstly, there is very little correlation to how busy someone is and the amount of work that gets done. 
Secondly, if you are under pressure there are various approaches you can take to create slack.

For instance, one way is to invest in practices that have a shallow dip and a quick recovery period. These practices may not necessarily be the most valuable long term practices, but they may be useful to create the initial slack needed to embark on the harder and sometimes more beneficial ones. 

The approach I like to use is as follows: 

- As a team, identify where the bottlenecks are. 
- Get an understanding of what practices can help reduce the bottlenecks and roughly how expensive the practices are to adopt. 
- As a team pick an appropriate practice, then spend time learning and applying it to your system. 

As the practice starts to realize a return you will have created additional capacity. Let your team re-invest the additional capacity to apply to the next identified bottleneck. 

Rinse and repeat several times. At some point you will create more time than you need for slack. When this happens your team becomes progressively faster and the interesting thing with getting progressively faster is that it becomes a drug. The faster you go, the faster you want to go.

----------------------------------------------------------------------------------------------------

So, with that said, let's move on to some actual practices.

## Automating and Democratizing the Build ##

The first practice I would like to talk about is automating and democratizing the build.

I've put this as the first practice because it is a low hanging fruit, yet I have come across many teams that don't do it. 

When I refer to the build I am talking about the set of files that are packaged or generated that are required to for a system to run on a test or production environment. 

For teams that previously released infrequently, this is usually a manual process owned by a single person. 

When you automate the build it means that instead of someone manually going through the steps to create a build, it is done automatically by a script file. Democratizing the build means anyone in the team should be able to trigger this process - even the non-technical people. 

How do you know if your build is automated? A good way to gauge is to ask a team to generate a build - if it takes them more than a minute or two, it is not automated enough.

Most teams I have come across that have not automated the build yet will tell me it is going to be very hard and that they have special circumstances that require a specific person doing it manually. Personally, I have yet to come across a team that hasn't been able to automate and share this responsibility across the team after applying their minds. 

For instance, I once worked with a team that was under a huge amount of pressure working on a very legacy application. There was one particular developer that stood out as always being busy. After some time with the team we noticed that every couple of weeks this particular developer would disappear for a day to make a build for the testers. Because of the pressure he was under, occasionally he would miss a step during the build process and send through a build pack with an old file. This would only get picked up after a few hours of it being with the testers which meant he would then need to spend another day re-doing the build and the manual testing would need start over again. You can imagine how popular he was when this happened and how much he enjoyed his build days. 

After quite a bit of encouragement we convinced him to give us time to help him automate the build. It took us a few days, but we managed to automate the build so that anyone could generate it. What once was an error prone process that took almost a full day of a developers time was reduced to a matter of seconds. 

The net result of this wasn't just creating an additional a day and a half a month of developer time. Automating the build made making the build painless. Things that are painless are done more often which in this case resulted in the team making smaller more frequent builds. Smaller more frequent builds resulted in more frequent releases which meant that business got features sooner than they had previously. 

If you have not automated and democratized your build yet, seriously consider it as a first line candidate.

----------------------------------------------------------------------------------------------------

### Version Control System ###

Leading on from builds is the practice of using version control. Version control is not just a fancy word for backing up code - one of the major advantages of version control is resolving merge conflicts. This means that many developers can work simultaneously on the same code base and the version control system will do the majority of the work involved in putting their code together as a single solution. 

I've seen version control frequently misused, abused or totally ignored by teams. One of the most common symptoms of misuse is when teams complain of regular merge conflicts. This is a symptom of the team not continuously integrating. 

Continuous integration starts with a discipline, everyone needs to continuously integrate to trunk.  If your team has murmurings of their version control system not working or how they hate it you are going to be dead in the water trying to get more advanced technical practices implemented. Make it a priority to get any pain in your version control resolved.

The pattern with version control is to do small little bits of work and merge or integrate frequently (in this case frequently means hours, not days).

----------------------------------------------------------------------------------------------------

### Continuous Integration Server ###

Doing smaller bits of work and integrating frequently means that people work closer together. When people work closer together, it becomes important to make build and integration issues visible to the team as quickly as possible. To do this, you need a continuous integration server. 

A CI Server, also called a build server, is a centralized server that builds your project whenever a check-in is done to the version control - it's responsibility is to build the code base from version control, making sure that everything is there and playing nicely. 

One of the big payoffs from a ci server is that it can make the general health of your codebase visible to everyone regardless of whether you are technical or not.

For instance, in a couple of teams that I have been involved with we plugged a monitor into our ci server that we put up in the team room. Whenever a developer committed work to version control, our ci server would automatically detect it, rebuild the solution and tell everyone how the build went. It used 3 colours - orange meant it was currently building, green meant that the last build was a success, and red meant we had broken something. Our team goal was try and keep the ci server green as much as possible. Whenever it went red, we would stop what we were doing and fix it immediately because we knew it had a major impact on everyone.

Making the ci server physically visible to the entire team helped us focus on sorting out integrations issues quickly and allowed everyone to keep it in the back of their mind that we were working together as a team on the same system. 

If you have already automated your build scripts and have your version control system working correctly, setting up a ci server is often trivial. It is something that every team needs to have.

----------------------------------------------------------------------------------------------------

## Collective Code Ownership ##

So, let's say you have your build scripts humming, your version control working smoothly and your ci server continuously integrating. What else can you get value from? It is at this point I would like to talk a bit about the practices that support the principle of collective code ownership.

Collective code ownership is the principle that code belongs to the project, not the individual. This means that anyone working on the system should be able to make changes to any part of the system without fear that they are stepping on someones turf. Why should this matter to you?

For one client we worked with the principle mattered because a developer went rogue and held the organization to ransom because he was the only person who understood a mission critical system. 

For another client collective code ownership is important because it reduces the bottlenecks on manpower. More people can work on a wider area of the system without waiting for a specific expert to be available. 

For me, it matters because I have found this principle supports better design, better code, fewer bugs and in general results in better systems being created. 

#### Common Code Style ####

One practice falling under collective code ownership is a team having a common coding style. By this I don't mean a thick document outlining exactly how everything is done and dictated by the architects in the architect forum - that doesn't work. 

I rather mean a team having a common understanding on what coding style their group has. It stands to reason that to have a common style, teams need to look and discuss code as a group regularly.

#### Collaborative Coding ####

One of the best ways to achieve a common style is to support collaborative coding. There are several different types of collaborative coding. On the diagram I have put up, the further right you go the more consistent I have found a team be in their common style. 

For some of you these terms may look unfamiliar. I'm going to briefly explain pair programming and mob programming.

Pair programming is the practice where two programmers sit in front of one computer solving a problem together. Mob programming is very similar, except instead of just two people, you have several people in front of a single machine solving a common problem.

Typically when I talk about collaborative coding and there are business people in the room, someone will ask how one can justify the costs of two or more people doing one persons job? If you have two programmers, surely they should be programming on their own work on their own machines otherwise they are not being efficient. 

The best way I can explain why these forms of programming work is by explaining what we mean when we say that someone is programming. Programming is not about typing, it's about problem solving. Depending on the problem being solved, there are many advantages to having more than one person working on the same problem. When we talk about pair programming or mob programming we are in effect doing group problem solving. 

Now a quick side note - one of the big complaints I have with most of corporate South Africa is that we are not making our work environments conducive to collaborative work. I see too many cubicles and desks that are not suitable for people to sit side by side and work at one terminal. The type of environments I want to see are ones where the background noise is reduced and the collaborative signal is amplified.

----------------------------------------------------------------------------------------------------

### Test Driven Development & Automated Testing ###

So, you have created a collaborative environment, the people are working well together, where do you go from here? There are a number of practices you can consider, as the last practice I'm going to talk about today, I would be doing you an injustice if I didn't speak about automated testing and test driven development.

#### TDD vs Automated Testing ####

In recent years I have noticed the growth in popularity of test driven development. However, in discussions with people who have not practiced any form of test driven development before, I find they get confused between test driven development and automated tests in general. 

Test driven development or TDD is a particular workflow that developers use when writing software. It involves first the developer writing an automated test that defines a desired improvement or new function, the developer then produces the minimum amount of code to get the test to pass and finally refactors the new code to acceptable standards.

The benefits of TDD include helping create a simple design and inspiring confidence in the developer that the code is doing what it is meant to be doing. 

Automated tests on the other hand are merely that, a set of tests that can be run automatically and written by anyone at any point in time to verify that a system is functioning as expected. Some automated tests can be written post development by testers. These types of tests merely verify that the system is operating as expected and yield no benefits to design.

#### Why TDD is useful ####

TDD is extremely useful. Firstly it teaches developers good design - in particular writing software that is loosely coupled. 

What do I mean by things being loosely coupled? The best analogy I can think of is this: If programming features was like building blocks, then pre-tdd I was making really big wooden blocks and using super glue to organize the blocks in the shape I wanted. 

Learning TDD taught me to make my blocks a lot smaller and them adjust them slightly so that they worked like Lego blocks - now, instead of having to glue things together I could just clip things in and out rapidly. 

In an agile world, where we embrace change, having code like Lego blocks allows us to change direction really quickly which becomes a major competitive advantage.

Now let me warn you upfront, if your engineers have not done TDD before, it can be challenging.

The first time I saw test driven development I saw someone demonstrate it by writing some code, running something, and a bunch lights on the screen went green. It looked really simple almost magical. I thought, great, all I need to do is go home and write tests and then I won’t have any bugs. 

So, I went home, spent a very frustrating day or two trying to write a useful test against the system I was working on at that time and I failed dismally. I could not write a single useful test let alone write it before I wrote its implementation - you see, the code I had written up to that point in my life was not unit testable. 

It took me more than a year of occasionally dabbling with TDD to understand how to do it, and another year to start practicing it, but once I began to get into it, I began to realize how powerful it is.

#### Best way to learn TDD ####

So, if it is so hard to learn, what is the best way to learn it? At a high level, there are two things you need to learn TDD : **Exposure and Time**.

For me, I needed a year to think about it and a few failed attempts at applying it before I got it. 

In terms of learning resources, probably the most I learnt about TDD was at a code retreat. Code retreats are a daylong event of intentional practice in a collaborative coding environment. In Johannesburg there are community ones that are free to attend once or twice a year on a Saturday.

Now, sometimes it’s challenging to get people with busy lives to attend events on their Saturdays. If you or your team are in this position I would recommend spending the money getting someone to come and host an internal company code retreat. 

I warn you though, don't expect to get TDD ninjas after one day at a CodeRetreat. It is going to take several positive exposures to the practice and an extended period of time applying it before you will see major returns. 

That said it is worth every bit of effort you put in to it because the return is so high.

----------------------------------------------------------------------------------------------------

### Closing ###

With that, we are coming to the end of this session. I have only covered five technical practices - these five are not the only technical practices necessary to operate at the release rate that agile methodologies work at, and you may find that the order they were proposed does not necessarily make sense for you particular team. That's fine, it's not hard to find your teams own natural order of progression.

All you need to do is:

1) Embrace the fact that we are all learning new things every day and that your team needs slack to learn  
2) Identify your team’s specific bottlenecks  
3) Be strategic in picking a new practice. Be willing to soldier the dips when adopting it  
4) Make improvement part of your daily process, not a special event  

With that I'm going to end off with a story - I call this my hope story - it's about a program called MaxCut. 

MaxCut is a program I have been involved in developing for several years. The first version was written many years ago before I was introduced to any of the practices I've spoken about today. 

In the early days of MaxCut we noticed the same effects we had seen in QuoteMaster - as we added feature on feature, it was taking longer and longer to make changes and keep everything working together and we were losing confidence in the system. 

One day I got email from a user asking for an really useful new feature to be added - at the time it I knew that part this would require us working on a part of code base that was very tricky and it was going to be several weeks if not a month or two. Since we didn't have that sort of time, I parked the feature request and put it in the "Nice Ideas but not going to happen" section.

A year later I exposed to many of the practices I've spoken about today. In particular, two of the things that made a big impression on me were ci servers and test driven development. 

With time we started refactoring MaxCut and applying these practices on the system. One day, I came across the feature request I had shelved a year or so earlier. 

It just so happened it was a Saturday morning and I had some free time. I wondered how much effort it would take to implement the feature now. I sat down, start working on it, I was surprised how confident I was working in the refactored code base. I was getting continual feedback from my tests and changing things was proving to be really easy. By the end of the day I had completed the feature, had run a full set of tests over the system and hand an installation available to distribute. 

What once would have taken months now had been accomplished in hours.

To me, that is the power agile technical practices. They make us go faster with time, not slower.

Thank you.

------------------------------------- END ------------------------------------- 
