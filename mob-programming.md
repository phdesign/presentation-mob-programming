# Two's company, three's a mob

## Intro and history

Around 5 years ago a development team at Hunter Industries in San Diego who were busy expanding their agile, TDD and peer programming techniques stumbled across a way of working together that later became known as mob programming. This technique continued to gain traction until now it's practiced world wide as an effective team development process with a dedicated mob programming conference held in Boston.

In the next 10 -15 minutes, or whenever Lars kicks me off stage, we're going to explore the world of mob programming, dispelling some illusions and hopefully give you an appetite to try it with your team. Assuming you are part of a team. If you're a freelancer you may want to sit this one out.

So back to our team zero, who are holding a solution design workshop in a meeting room and at some stage someone remotes back into their PC and they start writing code together while talking over the problem. Eventually they get kicked out of that room but find another and carry on, and in this way they continue to jump between meeting rooms for the next 2 weeks, programming as a team and everyday holding a mini retrospective and agreeing that this process is working for them and they should keep doing it.

## The mechanics

#### Driver / Navigator model

So how does it work? An important principle in mob programming is the driver / navigator model borrowed from strong pair programming, basically for an idea to go from your head into the computer it must go through someone else's hands. In mob programming there is one driver and the rest of the team are navigators. The driver sits behind the keyboard and types code. The navigators discuss the idea being coded and guide the driver in creating the code. This concept is critical to engagement of the team, if the driver starts thinking too much and typing their own ideas they'll leave the others behind, but having to clearly explain to the driver what to type, the navigators have to communicate and discuss the solution out loud. The driver is effectively taking a rest from thinking. Drivers are rotated on a short interval, this could be 5, 10 or 15 minutes. Shorter works better when starting out.

#### Equipment setup

A mob can be anywhere from 3 to 12 members and dedicated equipment is helpful. Meeting room hopping will quickly become tiresome and interrupt flow, so it's a good idea to setup a space with a couple of big TV screens or projectors, a single PC and any number of preferred keyboards or mice for those that like their mechanical clackers or splayed keyboards. At PageUp we'll often use this space although we find the contrast too low from the projector and usually use different IDE themes to improve the readability. 

#### Administrative tasks

During mobbing people aren't tied down for the whole day. Individuals are free to take short breaks to get coffee, go to the bathroom, check their personal emails or whatever else needs to be done. The mobbing doesn't need to stop because one person leaves.

In fact it can be helpful when working with new technology to go back to your own PC to do some research, or even better if you have a laptop handy bring that to the mobbing session. Ideally if you need to Google a solution this can be done as a mob, but there have been times we've paused the mobbing to all go away and research / spike a problem and regroup later.

If someone gets interrupted by and email, phone call or a walk up, some teams will even mob on that. Again it keeps everyone across what is being asked for and how we propose to solve it.

## The benefits

Mob programming offers a number of benefits over lone ranger development or pairing. 

#### Team cohesion & redundancy

It improves team cohesion. Mob programming necessitates that the team communicate effectively to get things done. This ensures that everyone in the team is across the current code and creates redundancy in the team. If one team member is off sick it will have little impact on the output. If a new team member is added they will be able to contribute immediately and will quickly learn from the others without distraction. 

#### Upskilling

It upskills existing team members as they learn new patterns, ways of thinking and tips to move around the IDE quicker. I find the first thing a new mobbing team learns is each other's shortcuts. Most developers hate watching someone else fumble through menus when there's a snappy keyboard shortcut to complete the task.

#### Quality control

Mobbing also provides improved quality control, having 5 eyes on the code will reduce typos and 5 minds on the problem will think through the majority of the scenarios. 

My team have been using mob testing lately as a twist on sprint reviews or showcases. The idea being that was we test and explore the product together, we spot more inconsistencies and decide how to resolve them as we find them. We also think through many more scenarios than we would on our own and by regularly passing control of the keyboard everyone is kept engaged in the process.

And mobbing isn't just for developers. Product owners, business analysts and testers are encouraged to be involved in the process. They can sit with the team and be apart of the discussion going on. 

## Common fallicies

1. The rest of the team will slack off while the person behind the keyboard does all the work.
   This is reason we rotate the keyboard on a short interval, people stay engaged and don't have time to tune out. It's obvious they're not paying attention if they get the keyboard and ask "so, where are up to?". 
2. Productivity will drop.
   Yes, the number of stories you deliver per sprint will definitely decrease, but the number of stories delivered isn't an accurate measure of productivity. Delivering working, fit for purpose software is a better measure. The quality of our code will improve when the whole team is focused on it which will mean less support and rework later. Better code is also easier to build upon and means future functionality can be implemented quicker. The quality of the solution will improve, by which I mean the team will discuss and agree on the requirements and how it will work. It won't get to done and someone says that's not how I expected it to work. And difficult problems won't hold up the team as much. How often do you find yourself working alone through a problem, only to have someone else look at it with a new lens and say "what if we did it this way". It can unlock the whole issue and allow you to move forward. This process is expedited if the whole team if focused on a problem at once.