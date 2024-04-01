---
layout: post
title: OculusDB hacking incident
tags: OculusDB hacking security
---
_last updated 2024-04-01_
# OculusDB hacking incident
Quick rundown cause I wanna go to bed now.

## Setup
It's april fools and as every year I try to do something funny and thus owoified everything on the mods page and OculusDB. OculusDB even got random font sizes and more random pranks I coded long ago.

## What happened
OculusDB and Mars (Mars being the server hosting OculusDB) were taken hostage by John/Johannes/Jonas.
Apparently some vulnerability in my server library caused this to happen and I'm still investiaging. They were able to successfully lock me out of Mars and due to some tokens being stored in plaintext even my discord server. You can check #general in the OculusDB discord server for more context.

He continued to rename the server to JohnDB and organize a Stage event. In dms he threatened to delete the backup he made of Mars if I didn't play along and pretended I didn't care much. He agreed to give me back access to Mars (partially for now) if I rebranded OculusDB to JohnDB for the next few days and kept the april fools stuff on it.

## Why did he do this
I don't know. Motive is unclear. I'd love to give you more insight into this but I can't

## Tips for you
Don't store tokens to accounts with administrative privilages on your server. Only give them the rights they need.

Have a fail safe account or server you can use to restore your server to a former state or even a recovery state with only one other user and password that's different from yours. 

And in general, don't trust your code. Try to use tools which have prooven themselves over decades instead of writing your own ones.