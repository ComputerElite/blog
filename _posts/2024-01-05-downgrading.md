---
layout: post
title: Why can't I downgrade with OculusDB
tags: OculusDB Oculus Login QAVS OculusDowngrader
---

# Index
+ Why can't I downgrade on OculusDB?
    * Info on accounts
    * What this means
* How can I currently downgrade?
    * Quest
    * Rift
    * OculusDB (not recommended)

# Why can't I downgrade?
So, why can't you downgrade games on OculusDB right now?
In the beginning of December 2023 Oculus changed how authentication for game downloads work. This means that you cannot download games anymore with the account on the [Oculus developer page](https://developer.oculus.com).

## Info on accounts
Even if you login with the same email and password, depending on the website you sign into, your logged in account has different permissions. For example when you log in on the developer page your logged in account does not have permission to download games. And neither does your account do on any other oculus webpage I'm aware of.

## What this means
You cannot download games anymore by simply signing into your browser.

# How can I currently downgrade?
## Quest (recommended)
The **currently recommended** way to downgrade is to install [QuestAppVersionSwitcher](https://sidequestvr.com/app/5333/) to your quest via [SideQuest](https://sidequestvr.com/setup-howto). You can then either follow the provided instructions (in app) to downgrade and mod Beat Saber or select ˋOther Gameˋ to downgrade other games (you **must** sign into your meta account in the tools & options tab to use the downgrade tab).

### Issues with downgrading in QAVS or Oculus Downgrader?
If you're having issues with downgrading, you're most likely signed into the wrong account. You **must** be signed into the same account your quest is signed into. You must also have bought the game you're trying to downgrade.
Check your quests settings to see the email you used for logging into your Quest and use that email to sign in.

## PCVR and Quest
Simply search for the game you want to downgrade on OculusDB and press the download button. You'll then get instructions on what to do.

## OculusDB
For OculusDB to work you'll need to get your token and install a browser extension.

You can get your token in the following ways:
* Install [Oculus Downgrader](https://github.com/ComputerElite/Oculus-downgrader/releases/latest), login and in the settings press export token to OculusDB
* (ToDo on my end) Install [QuestAppVersionSwitcher](https://sidequestvr.com/app/5333/) to your quest via [SideQuest](https://sidequestvr.com/setup-howto) and open the url shown in the tools & options tab on your PC. Then press ˋexport token to OculusDBˋ

After doing that you'll be prompted with which extension to install.

# Conclusion
I hope this clears things up. If you have any further questions feel free to join the [OculusDB Discord server](https://discord.gg/zwRfHQN2UY) and ask your questions there.