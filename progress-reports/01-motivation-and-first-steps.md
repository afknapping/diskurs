# Motivation and first steps

# What?

> An Internet forum, or message board, is an online discussion site where people can hold conversations in the form of posted messages. They differ from chat rooms in that messages are often longer than one line of text, and are at least temporarily archived. Also, depending on the access level of a user or the forum set-up, a posted message might need to be approved by a moderator before it becomes publicly visible.

> Forums have a specific set of jargon associated with them; example: a single conversation is called a "thread", or topic.

> A discussion forum is hierarchical or tree-like in structure: a forum can contain a number of subforums, each of which may have several topics. Within a forum's topic, each new discussion started is called a thread and can be replied to by as many people as so wish.

[Internet forum - Wikipedia](https://en.wikipedia.org/wiki/Internet_forum)

# Why?

Given the history and widespread use, it seems obvious that Urbit wants to offer forum functionality.

# How?

First of all, there is no wheel to re-invent here. Even if there was innovation to do, it would be contraproductive to onboarding new people onto Urbit. People usually want things the way they know them. \[lmk know if there are citations needed here, ~hocdep]

Though there is an endless plethora of forum software, [Discourse](https://www.discourse.org/) stands out for several reasons, summed up nice on [Discourse's about page](https://www.discourse.org/about):

> Discourse is a from-scratch reboot, an attempt to reimagine what a modern Internet discussion forum should be today, in a world of ubiquitous smartphones, tablets, Facebook, and Twitter.

![image](https://user-images.githubusercontent.com/170145/108705826-16f3cb00-750e-11eb-8f40-3a6deb9fa5ac.png)

The basic answer to `how` is: "Let's clone Discourse, of course while keeping our eyes open, and chop off everything that is not needed for a solid 1.0"


# Next Steps

I propose to divide the user journeys into four main blocks:

- Setup: what needs to be configured before people can start communicating?
- Onboarding: Inviting, joining, guiding
- Posting and reading
- Moderation (this especially needs the mentioned open eyes to accomodate for Urbit's p2p architecture)

Each of the four blocks should have a first rough outline with screenshots.

There should be dummy Discourse instance for the people working on the Urbit version.

There should be a clear prioritisation on what delivers the most value.

Since there is no innovation to do inititally, the emphasis should be on quality of functionality, not quantity ([Half, Not Half-Assed](https://basecamp.com/gettingreal/05.1-half-not-half-assed)).

