# Project -- Musoni

[Schedule](http://codeforgoodchallenge.com/?page_id=147)

# Sunday 11:30 coding cut off time! 

if on github -- just submit link
screenshots, project description

# Tech judging round

* Arch
* Teamwork -- how?

Output is a score

# Demo Presentation round

# Final Demo/Presentations


Take advantage of the Organisational Representatives

What exp does mentor have?

# Tech experts in:

* Android
* Java
* Python
* ...

Can also help with Arch, Debugging

# Tips

USE THE [WEBSITE](http://codeforgoodchallenge.com)! 

Use it to provision an Amazon EC2 server -- multiple stacks available -- Django
blah blah

They take a while to provision.

You can use GAE or Heroku, but EC2 doc is available

Be Patient & Brainstorm. Put together a good plan


Balance technology & Presentation.


# Charity Representatives

## Eneza

Background in education  -- teacher for 9 years

Goal is to make kids in Africa smarter

125,000 Students across Kenya, their impact is:
* 120,000, 15% raise in scores, 
* +2 more study hours per week

Provide tutoring services e.g. lessons, quizzes, via SMS & USSD -- old school

Time to get better!

Lual? Language

Kids have very little interaction with teachers, 1 teacher per 50? students

Huge surge in Mobile phones, nearly 100% of adults have mobiles

Low cost android phones

### What they need is an android app for TEACHERS / Parents similar to teachers

* Recieve reports based on how studetns are doing
* Live chat from SMS to web with students
* Assign Homework

It triples or quadruples their impact when adults are involved.

@EnezaEducation

[Emaail](Toni Maraviglia)
toni@enezaeducation.com

# Musoni -- The food chain

Cameron

Started during AIDS epidemic in 1978. They provided a hot meal. Now have lots of
medications, but food is ever more important to help medication work more
effectively. Bioavailability?

Majority of people affected in London. Prevalences is in central london --
Harringet, Hackney, Newham

54% of people who come to Musoni have a health problem. 84% have no money to buy
food.

27% have psychosocial barriers -- no motivation to eat well / cook a good meal
etc

26% don't *know* what food they should be eating.


100,000 People living with HIV

Package support designed for people delivered to homes

75 staff

10 voluntary dieticians place online grocery order

Cookery & Nutrition classes teaching them how to cook a nice balanced meal

## Challenge

Meal service -- started 25 years ago. Oldest service

Planned, cooked & delivered by volunteers

Staff only get involved for route planning, picking meals, dietary constrains
e.g. allergies

Route planning is bane of her life! Using a massive wall map & pins

Routes change every week. Houses may have 1+ HIV occupants, but they deliver to
the entire family.

Food prepped at 3 remote kitchens but this varies (up to 8)

Kitchen have max capacity based on oven space

2 hours delivery restriction -- volunteers can only drive for up to 1 hour


# Musoni -- meta-micro financial service

Enabling access to finance

## Challenge

# Social Entrepreneurs Ireland

A meta-organisation that supports for up to 3 years: social entrepreneurs

Currently supports 8 Social Entrepreneurs

## Challenge

11 - 18 SEs, working across multiple sectors, early stage and fast moving, small
team, limited contact with entrepreneurs

how do we comm more effectivley with the entrepreneurs?

Update, news, challenge -> Centrealised system -> Visually appealing output 1.
Portfolio (lives impacted, funds raised,) , 2. Individual projects

### Currently

* Annual reports
* F2F meetings
* Support Requests
* Monthly updates -- short summary of how each SE is doing (self-submission) via Excel
* Press Newsletters 

### Consider these:

1. Multiple sectors
2. COllects info relevant to the portfolio
3. Displays in a visually appealing way

"Irish start-up secures Euro300k to develop online programme for eating
disorders

# Agile dude Craig Larman

## Have an agile whiteboard so team progress/collaboration is easily visible to whole team

TODO | WIP | DONE 

What does "Done" mean? Does it mean it's Coded/Tested/Integrated?

Unit tests written/Passed/blah

Standup meetings -- Time boxed to e.g. 10 min, every 2 hours?

Round robin approach

What did I do that helped he team meet the goal? What will I do next to help team meet the goal


[Craig Larman](http://craiglarman.com)


## AspectJ blah

Separation of Concerns

Logging is in MANY places in org.apache.tomcat -- it's a *cross-cutting* concern! An *aspect* of the architecture. Logging is scattered throughout the code.

Session expiration? Again, a cross-cutting aspect

AspectJ: separates the aspect & *weaves* it in at compile time.

Very powerful -- e.g. you  can set preconditions on e.g. anything that takes an int assert that it's within bounds 10 < x < 50

Or you can call an `around` which traps the call before you make the call and clip the value and then call the method you trapped with the clipped value.

Defining `pointcut`s enables you to define sortof a bunch of things in the code that match a regex, so that you can use that group of matches later.

NullTester -- you want every method to check that the arguments to those methods are never null

Allows you to separate the concern of output by writing an `aspect Display`


	public aspect FakeDie
	{

	int around():
		call ( int Die.getFaceValue() ) // traps the call to getFaceValue and make it return somethign else {
			return 6;
		}
	}

can also do compile time testing

"Company policy: Only create objects via a factory" -- create a aspect to catch
o


