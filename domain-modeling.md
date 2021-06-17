# Domain modeling

## What is domain-driven design?

Domain-driven design (DDD) is an intuitive analysis to gradually explore a business domain and build software that supports it. It ensures a team has the right focus, and is able to take non-technical stakeholders along with them as a project progresses. It consists of strategic DDD and tactical DDD patterns to apply. Here we only focus on Strategic DDD, which elaborates:

1. **Bounded contexts**: Concepts that belong together and their relationships.
2. **Ubiquitous language**: Terminology to describe a bounded context for all stakeholders.
3. **Context maps**: How bounded contexts are related to each other.

Strategic DDD is universally applicable to capture knowledge of how a domain works. Tactical DDD _might_ be used in further translation to code, but is optional.

Bounded contexts on a context maps depict a breakdown into subdomains. In our elaboration there are 3 types of subdomain:

- **Core** domain: This is what the project/product is really about. The important parts that needs most attention and careful design, and where most value is added.
- **Supporting** domain: Different functional parts that support the core domain, but are less essential to what the project/product wants to offer.
- **Generic** domain: These are standard, often more low-level platform functionalities. They need to be present, but warrant less attention from a product perspective, and may be obtained as ready-made 3rd-party components where possible.

More info:

- [DDD Strategic Design in under 15 minutes](https://yewtu.be/watch?v=Evers5npkmE) (video, 14.38m)
- [Domain Modeling Made Functional - Scott Wlaschin](https://yewtu.be/watch?v=2JB1_e5wZmU) (video, 50.48m)

## Exploring current domain models

In this section we will look at each of the participating platforms in the Federated Hospitality Exchange project, and provide a description of their domain model as it currently exists. We will then refine this and elaborate further until we hopefully find some unified models that are the building blocks for future federated platform releases.

**Note**: Diagrams are created by [diagrams.net](https://app.diagrams.net/) and design files (XML) are available in the [`/diagrams`](https://github.com/FediHospEx/fedihospex.github.io/tree/main/diagrams) folder on Github.

### WarmShowers domain

Here is the diagram that captures the Hospitality Exchange core domain model of the current [WarmShowers](https://warmshowers.org) platform:

[![WarmShowers Domain Model](/diagrams/warmshowers-hospitality-domain-model.svg)](warmshowers-domain)

We will further refine this model as we go along the design process. See the [WarmShowers domain elaboration](warmshowers-domain.md) for more details.