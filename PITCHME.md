Progress and Plans

May 30, 2017

Sandro Hawke

---

Overview

- Motivation
- Funding
- The Adoption Problem
- "Trusty" architecture
- Flagship App: News with Friends
- Mastodon Success
- Mastodon Problems
- Flagship: Personal Walled Garden

---

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

- W3C Member Funding (other stuff: rdf data shapes)
- OpenSocial via W3C: Social Web standards
- National Science Foundation: Bootstrap Crosscloud at W3C
- Knight Foundation: Crosscloud for journalism

---

2017 Deliverables (High Level)

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

The Adoption Problem

Why Do Decentralization Systems Keep "Failing"?

* Ecosystem player motivations
    - Business Model, Politics
* UX

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

My Conclusions

1. the tech is too complicated (for mass adoption)
2. weak user value proposition (for mass adoption)
3. weak host motivation (for mass adoption)
4. not welcoming of decentralized extensibility
    - only core team gets to have fun/impact as coders
    - no room for 3rd party apps / vendors

All important, but extra focus on #4

---

"Trusty"

1. simple-ish tech (refining cyan)
2. user value: non-fake news, real knowledge
3. admin motive: commercial
4. dist-extn via template sentences (language-as-a-format)

---

Trusty: Flagship

<i>Friends helping friends understand the news</i>

Communicate via Agreement with Claims

and meta claims

---

Mastodon (Adoption?!)

- Decentralized Twitter, using OStatus, started in August
    - interop with gnustatus, postActive, ... (status.net)
- Appears to scale well (like email)
    - 1500+ servers
    - biggest servers ~100k users, so far
- phenominal success recently
    - pitched as Twitter without the bad people
    - Moderation by instance (site) admins
    - many UIs

---

Mastodon Issues

1. Bridging
2. Abuse
3. Ecosystem Fragility
    - pledge, faq, white-label
4. Site Lock-In
    - http forwarding
5. Groups =?= Sites

---

More Mastodon Issues

- 6 Socially-Acceptable Search (Context Collapse)
- 7 Algorithmic Feeds: Too Much/Little Content
- 9 In-Page Social Features // silo ecosystem
- 8 Apps: github, facebook, instodon,
    - games, resource sharing, health info
- 10 Interop for forks, new impls, protocol evolution

---

Steps

- [Shepherding issues](https://github.com/swicg/general/issues)
- W3C SocialWG
- W3C SocialCG
- Business Forum (W3C BG?)
- Discussions
- Tools & Demos

---

Building on Mastodon

_Personal Walled-Garden_

---

![Walled Garden](https://s-media-cache-ak0.pinimg.com/originals/78/7b/ca/787bcae2e766d62cf563c9dc6c1a7bc1.jpg)

---

Show me the stuff I want to see

And only the stuff I want to see

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

Later: additional UI features for nuanced reactions

---

Addresses Mastodon Problems:

- algo feeds
    - shows "best" of too much content
    - reaches out social graph, when too little
- bridging
    - feeds can include rss, reddit, maybe twitter, etc
- abuse
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

Summary

- impact before funding
- mastodon has momentum
- lacking feed manager, so provide it
- especially aim at social impact/journalism

