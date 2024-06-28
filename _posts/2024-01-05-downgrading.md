---
layout: post
title: Why can't I downgrade with OculusDB
tags: OculusDB Oculus Login QAVS OculusDowngrader
---
## Last updated Jun 28th 2024
### Revisions
- [Feb 29th 2024](https://github.com/ComputerElite/blog/blob/7505cd2c821943acf18f0e9bd421c4a7e04d207d/_posts/2024-01-05-downgrading.md)
- [Jan 5th 2024](https://github.com/ComputerElite/blog/blob/b7bea96ae98d919513b7fa3102e9145e799d3ee6/_posts/2024-01-05-downgrading.md)
# Index
+ Why can't I downgrade on OculusDB?
    * Info on accounts
    * What this means
* How can I currently downgrade?
    * Quest
    * PCVR

# Why can't I downgrade?
So, why can't you downgrade games on by downloading them directly right now?
Oculus removed download permission for the internal type of account I sign you in with. This means none of my downgrading tools currently have permission to download games from Oculus side. I've been searching for fixes for a few months with no avail so far meaning diff downgrading will have to be used for now.

## What's diff downgrading?
Diff downgrading is a way to morph the most recent version of a game into another one by providing steps on how to modify it. This way I do not distribute the older versions directly which is not allowed but instead instructions on how to get an older version, which mostly is. This requires manually creating diff patches tho which takes a lot of time and storage if I were to do it for every game every version. And even then I would have to get an old version of a game first which I only have of Beat Saber.

## Info on accounts
Even if you login with the same email and password, depending on the website you sign into, your logged in account has different permissions. For example when you log in on the developer page your logged in account does not have permission to download games. And neither does your account do on any other oculus webpage I'm aware of.

## What this means
You cannot download games anymore by simply signing into your browser or current downgrading tools

# How can I currently downgrade?
## Quest (recommended)
### **Downgrading only works for Beat Saber**


The **currently recommended** way to downgrade is to install [QuestAppVersionSwitcher](https://sidequestvr.com/app/5333/) to your quest via [SideQuest](https://sidequestvr.com/setup-howto). You can then follow the provided instructions (in app) to downgrade and mod Beat Saber.
Bear in mind that sadly only Beat Saber can currently be downgraded. And that only to some specific versions. QAVS will tell you which versions you can downgrade to.

## PCVR
This does not affect PCVR downgrading. You can use [Oculus Downgrader](https://github.com/ComputerElite/Oculus-downgrader) as usual to downgrade Rift/Air Link/Oculus Go/GearVR games

# Conclusion
I hope this clears things up. If you have any further questions feel free to join the [OculusDB Discord server](https://discord.gg/zwRfHQN2UY) and ask your questions there.
I'm searching for ways to get downloads working again. However it may take quite a bit till I find something if I find something at all.