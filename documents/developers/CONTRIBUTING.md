
# Contributing

## Contents
- [Contents](#contents)
- [Introduction](#introduction)
- [Pre Knowledge](#pre-knowledge)
  - [Code](#code)
  - [Documents](#documents)
- [Processes](#processes)
  - [Code Process](#code-process)
  - [Document Process](#document-process)
- [Internal Outreach](#internal-outreach)
- [External Outreach](#external-outreach)
- [Code Standards](#code-standards)
  - [Guests](#guests)
  - [Testing](#testing)
- [Document Standards](#document-standards)
- [Other](#other)

## Introduction
This set of guidelines is still in it's infancy, some sections may be incomplete.

Before contributing to this project, please read through this document.

You should make sure you:
- Know how the project is laid-out
- Know what the project is
- Know how the project moves
- Know that you need to contact some humans at some point
- Know who to contact
- Know what to contribute

With that in mind, here are some basic guidelines.

## Pre Knowledge

### Code

This repository has no code. Instead, this repository is for organizing a particular team of developers ("Team Blue").
If you want to make code contributions, make sure you are looking at the correct repository.
Since we are not hosting any code (we are contributing to someone else's codebase), we will be following their guidelines and using their tools.
You should familiarize yourself with whatever external project we are contributing to.

### Documents

What this repository does contain a lot of is design notes, meeting notes, final documents, and other paperwork.
These are all named, sorted, handled, and stored in a particular way.
The best way to learn is to just browse through the repository itself, most folders will have a `README` in them to explain what they are.
In general, you will want to pay particular attention to the [`DEVELOPERS`](../developers) folder, as this will have specific documents on document processes.

## Processes

These are general processes for how this team should conduct itself. These processes are designed specifically to help *a team* work better together.
As an independent individual, you may not find them especially useful.
In broad terms, these processes should vaguely resemble the [scientific method](https://en.wikipedia.org/wiki/Scientific_method).
Again, the code processes assumes we are contributing to some external group's codebase.

### Code Process

1. Spend some time studying the external group's codebase
2. Identify an interesting problem and take some notes on it
3. Write down your ideas into an **proposal-issue** on the [issue tracker](https://gitlab.cci.drexel.edu/courseeval/team-blue/-/issues)
4. Get feedback on your ideas and further refine your issue into a set of actionable **code-issues**
5. Some people will volunteer for your issues if you have made sure to engage them in dialog, if not, return to step 4
6. As you close your **code-issues**, reach out to the external group for submitting your patches, and consider whatever guidelines they have
7. On successfully closing your issues with the external group, close your issues here as well.

Now, as you may have noticed, this is just more work to contribute to the external group, as opposed to just working with them directly.
The whole point of this process is to involve the people on this team, hence why *reaching out* is so important.

### Document Process

1. Figure out what it is you are trying to say, how you want to say it, and who you want to have hear it

    - If you think there is an issue with how the team is behaving, create a new **team-issue**
    - If you want to propose some new feature or way of working, create a new **improvement-issue**
    - If you want to have an extended conversation, ping the team on [Discord](https://discord.gg/QKBxxSS9) and pick a date to meet up
    - If you want to quickly raise a point or ask a question, post it to us on [Discord](https://discord.gg/QKBxxSS9)
    - If you are afraid of asking everyone, message Peter ([peter201943#8017](https://discord.com/users/312363766954065930)) privately
    - If you feel the team is acting inappropriately, [send an email to the course instructor](mailto:hislopg@drexel.edu)
    - Everything else is a "formal document process" covered under [Document Standards](#document-standards) or in the [`DEVELOPERS`](../developers/) folder

    This is important because posting something to the wrong channel can lead to it being ignored.
2. Check for any templates

    Often, a template will exist, especially for remedial items (such as discussions, decisions, and issues).
    The point of the templates is save you time.
3. Write your document.

    If this is your first time writing a particular document, look at some past examples.
    For certain documents, they will have some special rules written out under the [Document Standards](#document-standards) or in the [`DEVELOPERS`](../developers/) folder.
    Since we are using [Git](https://en.wikipedia.org/wiki/Git) for all of the documents on this repo, do not feel bad about submitting incomplete or incorrecte documents!
    However, if you *abandon* your document, we will find you 😈.
    (Kidding aside, please don't just dump a bunch of documents and run).
4. Get feedback on your documents.

    In the spirit of democracy, try to involve the other members of the team when you can.
    When you are comfortable with your document, ping one or two team members on [Discord](https://discord.gg/QKBxxSS9) to get their thoughts.
    Alternatively, wait until the next meeting and bring up your document then (works best for proposals).

    Try to accept feedback gracefully. This can be difficult, so it may be worthwhile to look over the [Code of Conduct](CONDUCT.md) every now and then.

    This is also the last formal step of document writing, as you can return to step 3 and loop until you are satisfied with your document.
    At the end of the day, documents are a tool for communication. Once that communication has happened, it is time to move on.

Now, with the above, the use of Discord and Issues is strongly encouraged. If you are not familiar with how to use Discord, you should take some time to learn some Discord etiquette.
[A Suggestion for Discord Channel Etiquette](https://medium.com/@wysiwyg.comment/a-suggestion-for-discord-channel-etiquette-2b4d1a20ea0d) and
[the Discord Subreddit](https://www.reddit.com/r/discordapp/) can give you some tips on using Discord.

With regards to issues, it is very important to do three things:
1. Give your issues good names

    More than anything else, a good name can help everyone else on the team figure out what your issue is.
    It's often the first or only thing someone sees, and if it is not named well, the right person may skip over it.
    Give your issue a descript, but not overly verbose name.
2. Tag your issues appropriately
  
    Specifically, make sure to use all three *kinds* of labels (`Status`, `Task`, `Topic`).
    Each of these groups of labels helps the team to find your issue better.
    [Each label also has a short description](https://gitlab.cci.drexel.edu/courseeval/team-blue/-/labels).
3. Use the issue templates

    These templates save everyone time trying to both read through an issue and having to ask questions later.
    A few different kinds of templates should be available, and if you do not like any of them, feel free to edit one.

## Internal Outreach

You may have guessed by now that this project heavily revolves around communication.
One of the first things you will want to do is reach out to *someone*.
The best way to do that *internally* is to reach out to one of the teams.
All of the teams can be immediately reached from the [Discord](https://discord.gg/QKBxxSS9),
but for formal inquiries you should contact each team's *Primary Maintainer*.

**Team Red**'s Primary Maintainer is [*Hangyu Li*](mailto:hl664@drexel.edu)

**Team Green**'s Primary Maintainer is [*Katarina Galic*](mailto:kg896@drexel.edu)

**Team Blue**'s Primary Maintainer is [*Peter Mangelsdorf*](mailto:pjm349@drexel.edu)

**Team Purple**'s Primary Maintainer is [*Matthew Kirchheimer*](mailto:msk356@drexel.edu)

**Team Orange**'s Primary Maintainer is [*Mike Martin*](mailto:mjm682@drexel.edu)

You can also always reach out to the Course Instructor [*Greg Hislop*](mailto:hislopg@drexel.edu)

## External Outreach

Depending on what project we go with, we will add some guidelines for interacting with them as we learn them.

## Code Standards

### Guests
At the end of the day, we are guests to someone else's codebase.
You should learn whatever guidelines they have have and follow them.
This is not a lot of text, but the implications are big, you must study how the external group writes their code.

Otherwise, we recommend taking the time to thoroughly *document* and *test* your code.
[JavaDocs](https://en.wikipedia.org/wiki/Javadoc) and [Unit tests](https://en.wikipedia.org/wiki/Unit_testing) are a good place to start.

## Document Standards
Each document has a specific:

- Location
- Purpose
- Structure

You can find all of these in the [`DEVELOPERS`](../developers/) folder under the correspondingly named files.
You can also find blank templates for most of these documents, as well as previous documents to study as examples.

Briefly, the kinds of documents in this repository are:
- Discussions
- Issues
- Class Assignments
- Decisions

[**Discussions**](../discussions/) are like meeting notes, but over a much longer period of time. You can also think of them as working-notes.
These do not have an explicit formatting, but do have a general purpose of helping to build understanding.
Most occur on a daily basis, and are named as such using YYYY-MM-DD ([ISO 8601](https://en.wikipedia.org/wiki/ISO_8601)).
This is not a bad place to look for discussion on a particular issue.
You can also check the [Discord](https://discord.gg/QKBxxSS9) for any recent conversations as well.

[**Issues**](https://gitlab.cci.drexel.edu/courseeval/team-blue/-/issues)
are specific tasks assigned to specific people for specific periods of time. They contrast sharply with discussions.
Use these to get things done. These are the bread-and-butter of this project, and are likely going to consume the majority of everyone's time.

**Class Assignments** (most often Word documents) are requirements from the course instructor.
To make working on these as easy as possible, they are hosted online in a private Microsoft Team.
Most of these are pretty dull, but if you want access to any of them let [Peter](https://discord.com/users/312363766954065930) know.

[**Decisions**](../decisions/) are formal write-ups of particular rules or processes.
Given the narrow timeframe and scope of the project, these are going to be sparse and focus on just a few choices.

## Other
If there is anything else not covered here, reach out to the team.
This document is young, and open to suggestions.

Take Care.
