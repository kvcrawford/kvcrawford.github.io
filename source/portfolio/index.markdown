---
layout: page
title: "Portfolio"
date: 2013-09-21 17:20
comments: false
sharing: true
footer: false
---

## Tasty Mothertrucker
##### http://mothertrucker.herokuapp.com

_Tasty Mothertrucker_ was a 24hr hackathon project to present an idea for a product to my employer, Gunn/Jerkens. In its current state, it is only a prototype for the UI presented to new users.

It is intended to be a marketplace for connecting event organizers with food trucks: organizers would be able to browse food truck listings with an elegant user interface, enabling them to efficiently plan the catering for their event. Expanding on that, they could list their event for food trucks to bid on. Competition in an open marketplace would drive down costs, and food trucks would find more customers. Everybody wins.

I jumped at the opportunity to implement [AngularJS](http://angularjs.org/) to power the client-side view and controller logic. My findings are as such: _Angular kicks ass_.

## YuMe Plug, Play, Payday
#### http://yumeplugplaypayday.com

[YuMe](http://www.yume.com), a client of Gunn/Jerkens, is a leading provider of digital video brand advertising solutions. With the release of their mobile app SDK, they needed a compelling advertising campaign to drive developer registrations. While we were early in our design process, [KitKat](http://kitkat.com) and [Android](http://www.android.com/kitkat/index.html) launched immersive, scroll-intensive landing pages in a cross-product promotion for the launch of Android 4.4. I showed our designers this, prompting them to take inspiration and run with the idea.

They fired back with a nice, simple, flat design, and animation storyboards. Using the excellent [Skrollr](https://github.com/Prinzhorn/skrollr) parallax scrolling javascript library, I set to the task of implementing and fleshing out the finer nuances of the scroll-based user interaction.

I took it 90% of the way, including support for tablets. My coworker, [@monking](https://github.com/monking), added the finishing touches on the responsive CSS, to ensure a high-quality experience on mobile phones, as well.

## Playa Vista
#### http://playavista.com

Playa Vista is representative of a typical Gunn/Jerkens project: it is a housing development in the Los Angeles Westside ("Silicon Beach"), also consisting of commercial and retail space. I was responsible for providing input during the design phase, and taking a lead role in the development. Teammembers assisted in implementing the Google API-driven point-of-interest map, and other tidbits.

The same codebase powers a separate [blog](http://blog.playavista.com), easing future maintenance of both sites.

## East Garrison
#### http://eastgarrison.com

East Garrison was another project completed with Gunn/Jerkens, and much like Playa Vista, is also a housing development. A similar process was followed, with Git really shining in facilitating parallel development with [@apkostka](https://github.com/apkostka) to accomplish a tight deadline. Again, I focused on the overall architecture of the site, while he implemented the API map, timeline, and gallery.

## Gunn/Jerkens WP Boilerplate
#### https://github.com/GunnJerkens/wp-boilerplate

In an effort to make our lives easier at Gunn/Jerkens, [@apkostka](http://github.com/apkostka) and I set to the task of automating much of the work involved in starting a new project. It includes some theme boilerplate, plugins as Git submodules, default SASS/Compass configuration, and an initialization bash script. You clone the repo and execute the init.sh script, which

* Removes the current .git folder
* Initializes a new repo
* Loops through the submodules defined in .gitmodules, and re-initializes them as well
* Installs WordPress

I can attest that it has, in fact, made our lives easier.
