# Federated Hospitality Exchange

_Reclaiming reciprocal hospitality communities from boards and exchange platforms back to human interactions._

We’d like to take community-first approach, followed by technology. But it’s also very infrastructure heavy piece, so technically, we’re trying to federate different already existing hospitality exchange platforms to make it easy for new ones to emerge and evolve to keep serving their communities' needs - not the other way around. We'd like new communities to freely form, grow and re-form and for that we need new generation of software, flexible enough to be able to follow them.

**hospitality \[exchange\] platform**: a piece of software which connects travelers with those who want to host them. 

We envision a variety of platforms exist, built around specific communities' characteristics: for the bicycle touring community or for slow-travellers, in English and non-English languages, for women or lgbtq people only, gathering together families or even vegan families only, if they chose to enclose themselves in a community of their own. Some organized around democratic values and others with a strong leadership model. While all the platforms are independent and individual, they share common goal to connect travelers and hosts, and communicate with each other to better serve their communities.

In other words, we want to unify hospitality exchange communities into one big full-of-variety and everlasting community.

_Hospitality_ is a universal human phenomenon, practiced long before any software infrastructure existed. We can't imagine a platform like ours to fulfill its goals if it was not open, free and transparent for everyone and forever. This means for us [open governance](https://trello.com/c/VTpvnpv0), [open source software](https://github.com/FediHospEx/fedihospex.github.io) and [open finances](https://opencollective.com/fedihospex). 

Come, [help us!](#help-wanted)

## Who's involved in this? 

In the project are involved contributors to the platforms:
- [Open Alternative to WarmShowers.org](https://WarmShowers.bike)  - contributors to the community-built WarmShowers Android app, first released in 2012, before any WS board existed (2015), with which the community has grown (50+K installs in [Google Play Store](https://play.google.com/store/apps/details?hl=en&id=fi.bitrite.android.ws)), and whose access was cut off after WS board closed backend code (ca. 2017) and released a new paid app (2020), effectively excluding from the community members who access the platform from mobile devices only and for whom the fee for the new app is unaffordable (i.a. hosts from less developed countries, long-distance bike tourers). The devs and other community members made previously [many attempts](https://gitlab.com/-/snippets/2111860) to inform the board about the situation.
- [Trustroots.org](https://Trustroots.org)
- [WelcomeToMyGarden.org](https://WelcomeToMyGarden.org) 
- [BeWelcome.org](https://BeWelcome.org)
- [CouchSurfing.org](https://CouchSurfing.org) community members and builders, before it locked its community behind paywall

Potentially also:
- [Couchers.org](https://Couchers.org)
- [CyclePlanet.org](https://CyclePlanet.org)


## Why are we doing this?

* We aim to solve the issue of centralized boards ending up with too much power and locking their own communities in a platform the members cannot influence or move away from without:
  * excluding themselves from the community - right now, although a single user can relatively easily move from one platform to another, they can not do it [travelers] without losing access to the hosts on that platform and [hosts] while remaining discoverable for travelers who haven't moved (yet) - so **the community, as a whole, is trapped**,
  * losing history - 1. trust, often built on _reputation_ is very important for hospitality exchange. 2. connections and memories are so precious to many of us!
* We hope to grow network of (active!) hosts reachable from any platform…
* … and flexibility to choose who, when and where we’d like to host
* We hope to increase diversity of platforms so that everyone can choose what fits them best
* We hope to increase security and be more inclusive, and welcome new members from under-represented groups
* We hope to take off from existing platforms a burden of trying to fulfill needs of all without having a clear identity
* We hope to reduce the burden on developers maintaining the platforms to keep up-to-date in ever-changing technology landscape


## What exactly would change?

1. *from* **communities** locked in silos platforms with self-selected boards not representing communities values any more
   *to* **freedom to be on a platform of their choice, with variety of platforms existing, variety of governance, variety of communities to be part of while being part of wider network with many hosts available**
    - easy account migration between instances (nomadic identity)
    - discoverability of accounts (ex. usernames with platform prefixes)
    
1. *from* a few **platforms** without clear identity, competing with each other for users
   *to* the **bigger diversity of platforms with their own specific identity developed. Shared access to wide base of hosts** would relieve the burden on platforms to fulfill all needs, and they would not fear of missing out since other needs would be covered by other platforms. One could then imagine platforms in other languages than English or dedicated to certain life choices (think of ecology or veganism)
   - easy deployment of new instance
   - self-hosting and managed-hosting options for communities

1. *from* **users** jumping between multiple accounts, one for each platform
   *to* **single account and one search to query all platforms and find closest hosts among all of them**
   - single sign-on (cross platform identity)
   - visibility of existence of users across platforms (aggregated per location, no individual hosts)
   - linked accounts / guest account based on profile from the primary platform to reach out to users of the other platform
   - visibility of users across platforms (protocol what to include: location in 5km radius, username, …)
   - communication across platforms (aka matrix, ActivityPub)
   - a map with hosts from other federated communities

1. *from* **users** from underrepresented groups (non-english speakers, women, lgbtq, …) hesitating to participate because of fear of unsafe interactions
   *to* **the community, where everyone feels welcome, can find their place and group where they belong to, feel safe and can fully express themselves. Full diversity of members from all sort of backgrounds and groups equally represented in the community.**

1. *from* **devs-maintainers** competing with time to keep up to date with ever changing technologies, tired with maintaining outdated platforms,
   *to* **new platforms emerging every now and then with fresh ideas, energy and tech stacks. This can be achieved by making it easy for new platforms to start based on already existing ones and evolve them freely.**

1. *from* **platforms** keeping hosts forever despite them being inactive and unresponsive
   *to* **only committed hosts participating in the network on their own rules and preferences.**

1. *from* **users** exchanging direct messages 
   *to* **indirect hosting requests**

   > I travel and publish: Who can host me? \
   > Everyone in the network can see it and someone answers: come over to my home, we’ll be waiting this evening for you.
   
   - the request includes everything needed to determine for who it is relevant: (a) expected location and radius (b) current location, direction and speed (c) …

## Exploring possibilities

So there's work to do. In this section we link to documentation related to designing our future Hospitality Exchange platforms.

* [Domain modeling](domain-modeling.md)

## Other resources

Here you can read some more background, find other resources and places where we discuss, share ideas and connect with the world outside our core team:

* Our story is yet to be written down, but [here's a message](https://warmshowers.bike) that we, former WarmShowers Android app developers, display to the users of our community-built app, accompanied by short WS backstory

* [WarmsShowers Uncensored](https://gitlab.com/-/snippets/2111860) tracks censorious actions taken by Warmshowers, as well as other WS related resources.
  
* There is also a survey for WarmShowers users with [our values and pitch](https://warmshowers.bike/survey) for a new platform for bicycle touring community.
  
* BeVolunteer, an organization behind BeWelcome gives interesting [historical context](https://www.bevolunteer.org/about-bevolunteer/history/) of how hospex landscape was (r)evolving [[a backup copy](http://web.archive.org/web/20190809110251/https://www.bevolunteer.org/about-bevolunteer/history/)]

* [Github issue](https://github.com/FediHospEx/fedihospex.github.io/discussions/9) describing why we want to federate in the first place
  
#### Other useful places
* [SocialHub](https://socialhub.activitypub.rocks/c/fediversity/fediverse-futures/58) #hospitality tag, where we discuss federation using [ActivityPub](https://activitypub.rocks/), W3C standard protocol for decentralized social networks
  
* [Lemmy by HumaneTech](https://lemmy.ml/post/66076) brainstorming ideas, lemmy is like reddit but decentralized

* [Open Alternative to WarmShowers](https://www.facebook.com/groups/243374777243989) Facebook group

## Help wanted!

We are a group of developers, frontend and backend software engineers, so if you'd like to help with **social media** for example, you are _more than welcome!_ Please join our chat room to say _hi!_ and ask how you could help.

If you are a **developer**, join our chat room or just pick up an issue and start working on it. Here are contributors guidelines (todo).

We will likely spin up, rebrand and adapt an instance of Trustroots for **bicycle touring community**. If you'd like to help re-build this community in the new place, it's best if you could join Trustroots team as for now and self-organize from there.

Give us **feedback**, vote for **features** or ask **questions** on the board, it's very helpful too!
