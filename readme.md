# The LightSabers Guild Kata

[![Join the chat at https://gitter.im/rhwy/cleancode-lightsabersguild](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/rhwy/cleancode-lightsabersguild?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


## What's about ?
Hey, I'm the boss of LightSabers guild, a company specialized in selling real
Light Sabers all across the Republic.

On our website, during the registration process we planed to collect some user data, and
later, another process within a batch will send a registration mail to the users,
for confirming their mail, based on a template we provide and that data the
user has input.

That's a very basic feature! So, we put a junior developer on it but the team lead
had to put him on an important production bug fix before he finish it. After all,
it's just a mail validation, it can wait, it's not critical in our business.

I know you're new in the team but let's see if you can do something for me, ok?

As the rest of the team are staffed on another project you will report to me directly.
Even if I'm not a tech guy, because it's very simple I'm pretty sure we'll manage
to build that quickly! Take other available interns with you if they are available
to help, maybe you can divide even more the time needed to accomplish it!


## Step 1 - Finish It !
Now, as far as tech team told me, it has only a small bug but it's quite ready to
production. The first step will be to package it for use along with our batch scripts,
it's easy, it will not take you anytime.

Don't spend too much time with it because we already have a _very small change_ in mind.


## Step 2 - A small change!

Actually the website register one data file for each user input but last week we
put online a mobile version too and that team told me that it can't be done like
that and they changed the format of the data. For the mobile website, we have now
an Excel compatible file format with all data (they put users in rows and values
separated with comas or something like that). It will also improve our capabilities
because you only need to read one data file.

The only point you need to take care is that we need to support both mechanisms with
that tool because it will be the same for both desktop website and mobile website.


## Step3 - not a step ...

I attach a lot of attention to the quality of our products, I don't know if it is
possible in development because it's always crappy but try to do your best on it, right?

Don't forget also that :

* it's a tool to integrate in our batch system that must be scriptable and then called with the different options
* I want to see the value you provide to me with it
* I want you to prove me that it works
* I want you to make it clean and documented for the next developer to make changes.
