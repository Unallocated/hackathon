---
layout: home
title: Unallocated Space Hackathon1
---

## Oh no. Not this nonsense again...
Yup. It's back. More pizza. More code. More hardware hacking. More sleep deprivation. More frustration from beating our
heads into the same stupid problems again and again. More Wompster.

Oh yeah. This is a thing.

Here at Unallocated Space we have long experienced the woes of an outdated, underdeveloped, underdocumented, and
highly unstable core services infrastructure. Through inspiration that can only be described as drunken revelry, our
forefathers brought forth these miraculous technologies in the true spirit of hackerdom.

At the last hackathon we were able to make absolutely *MASSIVE* progress on all fronts. We're following up on the
success of the last event with *ANOTHER* old school, red eyed, energy drink fueled, hardcore, 24-hour hackathon.

## So Much Code, It'll Make You Puke
We've got a LOT of projects that need help. Click on a project to learn more about it and to find out who's running it.
Here's a list to start, check back often as updates will be posted here. Languages will be on a per-project basis.

<ul>
{% for project in site.projects %}<li><a href="{{ site.baseurl }}{{ project.url }}">{{ project.title }}</a></li>{% endfor %}
</ul>

## Not Just Developers
So much more goes into a project than just constantly spawning code. It takes an army of people to develop a quality product. Don't know
how to code? You probably have a skillset that we need anyway.

We need:

<ul>
{% for role in site.roles %}<li><a href="{{ site.baseurl }}{{ role.url }}">{{ role.title }}</a></li>{% endfor %}
<li><a href="https://www.youtube.com/watch?v=RYMH3qrHFEM">Developers</a></li>
</ul>

## But I'm Not a Member of Unallocated
Membership is not required to participate.

Come on down and jam out with us. If you like what
you see and you'd like to be a part of our community, we have [memberships available starting at
$25/month](http://www.unallocatedspace.org/uas/donations-and-dues/). We also accept one time donations.

No donation is required for this event. All "staff" of Unallocated Space are volunteering members -
all donations go towards keeping the lights on and keeping this resource available to the community.
[Learn more about Unallocated Space](http://www.unallocatedspace.org/uas/about-us/).

Membership is required to be a Project Lead. These are critical resources and will require guidance
from people who are invested in the community.

## What Should I Bring?

#### Laptop/Computer
Bring your own laptop or workstation prepared with the appropriate environment to perform the task
that you will be undertaking. Both wireless and wired connections are available. You may bring a
second monitor. While we do have some equipment available, Unallocated Space does not provide any
software and cannot guarantee the availability or operability of any equipment on site.

#### Github Account
We will be using Git based workflows and open sourcing these code bases, distributing through Github.
A Github account will be required to submit pull requests. If you don't have one [signing up is easy!](https://github.com)

#### Food and Beverages
Unallocated Space will be providing:

* Energy drinks
* Soda
* Bottled water
* Coffee (I'll have a keurig, so you can bring your K-Cups)
* Pizza (Consider this for snacking - you should plan to provide your own meals)

Everything mentioned here is subject to limited availability, "first come, first serve".

You should bring any food or drinks that you'd like for yourself and any food or drink you would like to
donate to the other participants.

#### Alcohol
We will be making an exception to our hard liquor rules for this event. You may bring your own beer, wine, liquor, and
and mixers.

Underage drinking and drunk driving will be dealt with severely and reported to the appropriate authorities. Please do
not test this.

While we will be allowing liquor during the hackathon, please exercise good judgement. We reserve the right to revoke
this privilege for specific persons, for whatever reason. This is only allowed because there were no incidents last
time. Remember that this event should focus on the development tasks, and not on the drinking. Let's keep it fun.

#### Comfortable Clothes
Wear clothes that you can sit around in for long term and that you're comfortable working in. PJs are okay, but nothing
revealing please. Despite what you may think, we don't want to see your naughty bits.

If you're staying overnight, we ask that you bring a change of clothes so that you're not quite so
schmelly.

#### Deodorant
Nerd funk is not a myth. Seriously.

There are no shower facilities at Unallocated Space.

#### Headphones
I'm betting that our music will be terrible. Come prepared.

## Is There an Age Limit?
Between the hours of 9pm Saturday through 9am Sunday will be 18+ only.

Children under 12 should be accompanied by an adult.

While there is otherwise no age restriction, this event is not targeted to youth. We would love to
show your kids how much fun code can be, but expect foul language and alcohol consumption.

## No Cowboy Developers Here!
Okay, maybe a little.

We will be adhering to [recommended Git workflows](https://guides.github.com/introduction/flow/index.html).
We will be doing so a little less than strictly, and at the discretion of the Project Lead for that
project.

We will be hosting a [Git workshop]({{ site.baseurl }}/gitworkshop) before this event to teach the basics of Git, and how to work within a
Git based workflow.

## Well, I'm Really Not Very Good...
So? There's some truth to the fact that you should have some foundational knowledge in whatever technology you're
working with, but we're not expecting experts here. Work together and learn from each other. Skill levels can range
from beginner to advanced.

## I Can't Carve Out a Whole Weekend For This
You do not have to be here for the whole 24-hour period. There are some of us that love this sort of thing, but stop
in when you can, and help with what you can. There will also be a lot of preparation work before hand that we will
need help with as well. We'll take what we can get.

## Registration
If you know you'll be coming to this event and would like to take part, it would really help us out a lot if you
[registered for your project]({{ site.baseurl }}/register). It only takes a second and this helps us know who will
be attending and what resources are available for each project.

## Okay, I'm In. Where's It At?
{% include location.html %}



