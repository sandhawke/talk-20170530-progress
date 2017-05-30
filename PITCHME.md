
class: middle, center

Progress and Plans for 2017

Sandro Hawke

May 30, 2017

---

Overview

- Problem Space
    - Motivation
    - Funding
    - The Adoption Problem
- Pre-Mastodon    
    - "Trusty": News with Friends
- Mastodon Success
- Mastodon Problems
- New Flagship: Personal Walled Garden

---

class: middle, center

Goal:

Tip the balance
against
social software lock-in

---

Why? Three Examples:

- personal health data in silos
- political news controlled by silo providers
- resource sharing (eg uber) in silo battle

---

Funding in 2017

- W3C Member Funding (for non-crosscloud work)
- OpenSocial via W3C: Social Web standards
- NSF: Bootstrap Crosscloud at W3C
- Knight Foundation: Crosscloud for journalism

---

2017 Deliverables

- bootstrap crosscloud ecosystem
    - show solid evidence of adoption
    - toward clear social benefit

- not publications

---

Thoughts on Funding for 2018

- should be based on success in 2017 (proof points)
- Likely goals:
    - civility and truth, online
    - healthy communities
    - connecting members of a profession
        - "twitter at work"
- domains: news media, science, health, marketing

---

Funding Landscape

- Industrial:  W3C membership, W3C BGs, Media Lab
    - Intermediated Content Providers
    - Knowledge Workers 
- Foundations: Knight, MacArthur, Omidyar, Sloan
- Gov't: NSF, NIH
- Partners: EU SemWeb

---

class: middle, center

The Adoption Problem

Why Do Decentralized Systems Keep "Failing"?

---

- Low-Crypto
    - Diaspora* / Friendica / Hubzilla (15k mau)
    - status.net / gnustatus / postActive
    - IndieWebCamp
    - [24 others](https://en.wikipedia.org/wiki/Comparison_of_software_and_protocols_for_distributed_social_networking)
- High-Crypto
    - IPFS
    - MaidSafe
    - Scuttlebutt
    - [14+ others](https://www.scuttlebutt.nz/#other_projects)

---

 Roughly:

* Ecosystem player motivations
    - Business Model, Politics
* UX


Or:

1. the tech is too complicated (for mass adoption)
2. weak user value proposition (for mass adoption)
3. weak host motivation (for mass adoption)
4. not welcoming of decentralized extensibility
    - only core team gets to have fun/impact as coders
    - no room for 3rd party apps / vendors

All important, but extra focus on #4

Pre-Mastodon

---

class: middle, center

trusty.media

---

Trusty Media

- Flagship App for "Trusty" Platform
- <i>Friends helping friends understand the news</i>
- Communicate via Agreement with Claims
- and meta claims

---

Trusty Architecture

1. simple-ish tech (refining cyan)
2. user value: non-fake news, real knowledge
3. admin motive: commercial
4. dist-extn via template sentences (language-as-a-format)

---

background-image: url(https://github.com/sandhawke/mastodon-talk-201705/raw/master/fediverse.png)

class: middle

# Mastodon

---

Mastodon (Adoption!)

- Decentralized Twitter, using OStatus, started in August
    - interop with gnustatus, postActive, ... (status.net)
- Appears to scale well (like email)
    - 1500+ servers
    - biggest servers ~100k users, so far
- phenominal success [<a href="https://radar.amberstone.digital/chart/fediverse" target="_blank">radar</a> <a href="https://metadon.jemu.name/#users" target="_blank">metadon</a> <a href="https://dashboards.mnm.social/" target="_blank">mnm</a>]
    - often pitched as Twitter without the bad people
    - Moderation by instance (site) admins
    - many UIs

![mastodon logo](https://assets.mastodon.social/packs/fluffy-elephant-friend-cc7707eb7d15da8501a56e0c5a4fb238.png)

---

Major Issue: Ghost Town

- Appears solved
    - Community instances
    - Massive march influx
    
---

Major Issue: It's One More Silo

- Some people want their _existing_ content sources
- Some people want their _existing_ audience
- (simultaneous migration problem)

Solution? Bridging

- Technology: challenging
    - silo API via bridge site like brid.gy
    - eg sandhawke@tw.multi.social
- Social: challenging
    - opt-in by followers
    - opt-out by individuals
- Legal: challenging
    - Facebook v. Power Ventures
    - politics

---

Major Issue: Selecting An Instance

- How do you pick your new identity?
- Who do you trust to host?

Solution?  Improve the Market

- Standardize ToS
- Anti-Lock-In Pledge
- [Admin FAQ](https://github.com/sandhawke/admin-survey/blob/master/README.md)
- White-Label hosting
- Non-Zero-Price hosting

---

Major Issue: Instance Lock-In

- What if you don't like them any more?
- What if they're shutting down?

Solution? HTTP 3xx Redirects

- 80% solution: only works at a level of decency
- Current implementations are weak on this
- Likely within reach, with a push

---

Major Issue: In-Page Social Features

---

Major Issue: Interop Beyond Mastodon

---

Major Issue: Beyond Microblogging

- other areas: github, facebook, instodon,
- games, resource sharing, health info

---

Steps

- [Shepherding issues](https://github.com/swicg/general/issues)
- W3C SocialWG
- W3C SocialCG
- Business Forum (W3C BG?)
- Discussions
- Maybe: Tools & Demos

---

Major Issue: Social Climate

- Spam
- Bots
- Unacceptable views (Nazis, feminazi, ...)
- Clickbait
- Echo Chambers
- Criminal activity (dark web)
- Identity verification
- Acceptable use policies
- Veracity management (fake news)

---

Major Issue: Algorithmic Feeds
- Too much content
    - follow lots of people, good content gets lost
- Too little content
    - following the wrong people
    - not following enough people

---

More ...

- Issue: Group !== Identity, Instance !== Community
    - Participate in conversation without new instance  
- Issue: Socially-Acceptable Search

---

class: middle, center

_Personal Walled-Garden_

(Built for Mastodon)

---

background-image: url(https://s-media-cache-ak0.pinimg.com/originals/78/7b/ca/787bcae2e766d62cf563c9dc6c1a7bc1.jpg)

---

_Show me the stuff I want to see_

_And only the stuff I want to see_

Guided by conscious (better-nature) decisions (not ad revenue)

---

feed.studio

* create 1+ feeds for yourself, others
* tend each feed, guiding it while it grows
* private feeds for outbound control

---

Possible MVP within Mastodon UI

* @new@feed.studio to create a feed
* follow it to see stuff it's got
* @feedNNN@feed.studio, or react to items to adjust it
* can be viral, as people discover feed

---

Natural Web UI

* feed profile, posts themselves, hosted on custom instance
    - details on why selected
    - more feedback options
    - shareable away from Mastodon

Later: additional UI features for nuanced reactions (push extensibility)

---

Addresses Mastodon Problems:

- algo feeds
    - shows "best" of too much content
    - reaches out social graph, when too little
- bridging
    - feeds can include at least rss
    - maybe more-open systems: reddit, tumbr, github
    - possibly twitter, instagram, ...
- social climate
    - tunable blocking, sharing block info
    - make content visible to feeds, access controlled

---

Addresses Mastodon Problems:

- groups =?= sites
    - keep group-identity sites, but allow non-resident participation
- acceptable search
    - depth-first in algo feed
    - maintain opt-in context, avoid triggering

---

class: middle

background-image: url(./garden-faded.jpg)

<div style="font-size: 150%">
<p>Summary</p>

<ul>
<li>impact before funding</li>
<li>mastodon has momentum</li>
<li>help it steer around dangesr</li>
<li>provide helpful feed manager</li>
<li>especially aim at social impact/journalism</li>
</ul>
</div>
