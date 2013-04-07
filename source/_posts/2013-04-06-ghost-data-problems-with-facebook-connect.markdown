---
layout: post
title: "Ghost data problems when using Facebook Connect"
date: 2011-02-09 18:22
comments: true
categories: 
---
I have to admit -- I am pretty loose with my Facebook Connect credentials. Any startup that has a pretty front-end and pretends to be at least working towards obtaining seed funding can have a free ride with my Facebook login (using protection of course, aka cryptography-free OAuth 2.0 over https) as long as I know they won't post to my wall without my consent. I suppose I should have higher standards so that groomed front page marketing messages won't instantly woo me into clicking the shiny blue fb login button.

But when it comes to Gen Y browsing habits online, I'd say perennially laziness, short attention spans, and unreasonable trust (did I even check if that page is using SSL before entering my bank account information?) are hallmarks for which I am no exception at avoiding. Thus, my interest in playing with every new startup on the block combined with my resistance for creating new accounts for each one, makes logging in with Facebook Connect the ideal solution for me. It's easy, it's painless, and I'm always logged into Facebook so within 2-seconds I'm in. Facebook Connect has never caused me problems that I've known of so I haven't had to reevaluate my reckless behavior, until now.

Today I received a new subscriber on Plancast -- a site that aggregates friends events and activities from multiple services (Facebook, Eventbrite, Meetup, Google Calender, etc) in order to better recommend activities you would enjoy as well. I hadn't visited Plancast since April 2010 when I originally connected my Facebook account to create a user profile. I logged on today for the first time (when notified of the new subscriber) and was confronted with the following profile:

{% img /images/plancast.png %}

This screenshot disturbs me for several reasons. (1) My new subscriber was a 'professional' contact, thus (2) I never wanted "The Devil from Acapulco" @ a sketchy nightclub to show up for public view, (3) Wait what? I never even remember saying I was planning on attending that event, how did that get there in April 2010?!?, (4) What and where is other "ghost personal data" from Facebook being displayed without me even realizing?, and (5) Can I delete and remove this ghost data from my application profiles now that it has already been pulled and saved externally?

Unfortunately, in Plancast's case, I can't delete past content or events I've so-called attended, only upcoming ones. This is bad. I should have complete control over my data -- even data automatically pulled from APIs I asked to be linked to the current application.

Other problems with using Facebook Connect for logging in:

1) User oversight in understanding how her data is being used currently and no information about how it will be used in the future. If apps change how they use personal data, the user may not be informed and the data remains publicly visible in many different locations, in manners not originally intended at the time of connecting to the application.

2) User forgets that she connected her Facebook account 299 days ago. Might not ever become top-of-mind unless if a notification is pushed to the user, at which point, it might be too late or inconvenient; who has already seen the compromising information the 298 days before I bothered to log in again? Additionally, the data is stale at this point, degrading the application's experience.

3) User succumbs to mindlessly accepting pop up dialogs. As Joel Spolsky of Fog Creek wrote in 2000 (a classic?) "Designing for People Who Have Better Things To Do With Their Lives":

In fact, users don't read anything...experience shows that the more words you put in that dialog box, the fewer people will actually read it. Experienced UI designers literally try to minimize the number of words on dialogs to increase the chances that they will get read.

{% img /images/fakerequest.png %}

Would you notice what was wrong with this dialog? I wouldn't; it's so comfortingly Facebook branded.

I suppose it's fine if I continue being loose with Facebook Connect, allowing my account to sow oats in the wild, wild web. But I have to be prepared to face the consequences of my ghost data (children?) being left all over the internet without my knowledge. Right now Facebook says:

You're using 125 apps, games, and websites...

Clearly I have some gutter cleaning to do.