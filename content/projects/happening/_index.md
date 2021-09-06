---
title: "Happening"
date: 2021-09-05T23:45:37Z
draft: false
links:
    github: https://github.com/davidhollis/happening
---

A web application for managing and messaging about social events. I got frustrated with Facebook events--I disliked that I could only invite people who had active Facebook accounts, and the limited privacy settings made it hard to share links to the event without exposing it to strangers. When I looked outside of Facebook, I found services loaded with ads, or that made it surprisingly difficult to simply RSVP.

I ran a small survey, and from the results of that distilled the the following two principles that are guiding the design process:

  1. **It should be privacy-focused:** Anyone using the application in any capacity should have full control over who can see any data pertaining to them, and what notifications they receive from the site. Guests should be able to determine how they present at any event (name, pronouns, photo) without having to create and manage alt accounts. **In addition, there will be no form of advertising on the site, as that inherently compromises the privacy of users of the service.**
  2. **It should be low-friction:** Event organizers should be able to invite people who aren't already signed up, and guests shouldn't have to complete an onerous setup process just to indicate they're going to an event. Nobody should have to remember yet another password.

The backend is being written in Scala, using the [Play Framework][play].

[play]: https://www.playframework.com/