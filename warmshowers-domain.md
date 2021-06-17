# [WarmShowers](https://www.warmshowers.org)

## Context map

The domain of the current WarmShowers platform consists of the following subdomains that are part of its Context Map:

- <b>[Hospitality Exchange](#hospitality-exchange-domain)</b> core domain: Allows Hosts to be found by touring Cyclists and Cyclists to find Hosts to stay with during their trip.
- <b>[Membership](#membership-domain)</b> generic domain: Allows Members to register on the platform.
- <b>[Social](#social-domain)</b> supporting domain: Allows Members to present themselves and provide feedback.
- <b>[Messaging](#messaging-domain)</b> supporting domain: Allows Members to communicate in order to plan a stay.
- <b>[Funding](#funding-domain)</b> generic domain: Allows Members to donate to the project team.

Note: A Community subdomain exists implicitly; all platform members together are the WarmShowers community.

## Subdomains

### **Hospitality Exchange** domain

<div align="center" markdown="1">

![Hospitality Exchange domain model diagram](/diagrams/warmshowers-hospitality-domain-model.svg)

<small>_(Diagram [source](/diagrams/warmshowers-hospitality-domain-model.xml) created by [diagrams.net](https://app.diagrams.net/))_</small>

</div>

Actors:

- A **Host** is a Member that provides a place to stay
- A **Traveller** is a Member that seeks a place to stay

Ubiquitous language:

- Host offers **Accomodations** to travellers
- Host presents **Host Profile** to travellers
- Host specifies **Availability** of accomodation
- Hosts are displayed on a geographic **Map**
- Traveller filters Hosts on Map by **Search Criteria**
- Traveller searches Hosts by **Search Criteria**
- Traveller bookmarks Host Profiles to return to later
- Traveller contacts Host to plan their travel<br><br>
- _Traveller arranges a **Stay** facilitated by a Host_
- _Traveller might get **Amenities** provided by a Host_

Notes:

- Travellers are also known as 'cyclist', 'bicycle tourer', 'bicycle touring traveller' or 'cycling tourist'.

- Hosts use the host profile to present themselves to other members.
  - Profile may contain more detail on accomodations and amenities.
  - Amenities can be: tools availability, distance to bike shop, bike storage available, private or shared bathroom, mailbox available, ...
  - Amenities are mostly not on the host profile, but may be offered once host and traveller get to know each other better.

- Accomodation details are: accomodation type, number of guests, ...
  - Accomodation types are: tent spot, bedroom, ...

- Availability statuses are: hosting, not available, in a long distance touring mode, ...

- Search criteria are: host name, location, accomodation details.

- Bookmarks store host info for offline use, and are used to e.g. plan a trip ahead of time.

### **Membership** domain

Actors:

- A **Member** is a person with a **Member Account**

Ubiquitous language:

- Person selects a **WarmShowers Instance** to join
- Person creates new **Member Account**
- Member validates Account email address
- Member requests new Account password
- Member logs in to interact
- Member migrates Member Account to another Instance

### **Messaging** domain

Ubiquitous language:

- Member sends Private Message to other member(s)
- Member receives Message in **Message Inbox**
- Member replies to a Message
- Member deletes or archives Message
- Member has a **Message Archive**

Notes:

- Members also communicate directly by sms, phone, or email if they want to

### **Social** domain

Ubiquitous language:

- Member has a **Member Profile**
- Member can provide **Member Feedback** to other members
- Member can view Member Feedback of other members
- Member can publish **Stories** for other members
- Member can share Stories to **Social Media Channels**

Notes:

- Social Media Channels are: newsletter, podcasts, Facebook group, Instagram
- Members also find touring partners on the WarmShowers Forum

### **Funding** domain

Ubiquitous language:

- Member / Person donates to WarmShowers project team

Notes:

- Recently member donations are visible to all members.
