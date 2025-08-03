# cOHMunity/README

Hi and welcome to the cOHMunity :)

We’re working with developers, researchers, and diverse communities to build WisdOHM, an open source system for quantifying the relative value of diverse contributions to any given collective mission, so that we can empower and connect communities in pursuit of the common good. WisdOHM is our particular implementation of the Metavaluation framework, which we're developing in parallel for public use and collaboration. 

### How it works
Contributions can be recorded and peer-reviewed by any member of the community. Reviews are completed as pairwise comparisons: voting between pairs of contributions on one or more dimensions of interest to the community. Open source algorithms then convert these data into standardised metrics, which serve to (a) recognise the unique qualities of each contribution, (b) reward contributors automatically, and (c) respect contributors for the value they provide. 

### How is WisdOHM different?
The key innovation of WisdOHM is the way in which pairwise comparisons are used to peg the value of all other contributions. WisdOHM treats pairwise comparisons as valuable contributions in their own right, assigns them a standard unit of value, and includes them in the contribution set to be reviewed. This gives rise to meta-reviews (reviews of reviews), where one of the two items being compared is itself some number of reviews. Meta-review votes are then used to ‘weight’ the value of regular contributions, producing relative valuations where each unit is equivalent to the value of a single pairwise comparison.  (-> [read more](https://github.com/openheartmind/cOHMunity/wiki/Metavaluation)). 

### Background
WisdOHM began life as an open evaluation (or peer-review) model and evolved through experiments at [Open Heart + Mind](https://openheartmind.org/) (OHM) to become a flexible framework for diverse contexts and communities. We prototyped in [spreadsheets](https://docs.google.com/spreadsheets/d/1kQJM2kEVulzwXBQZuvR46wxaQY5_ohm0rbndIkdEkSE/edit?usp=sharing), built a proof-of-concept web-app (deprecated), a working prototype (live, see below), and are now building an MVP.  (-> [read more](https://github.com/openheartmind/WISDOM/wiki/Development-History))

### Use cases
WisdOHM is designed to be simple yet flexible, so that it can be applied to diverse use cases. At OHM, we’ve explored WisdOHM in the context of [festivals](https://openheartmind.org/wisdom-prototype-tiny-ohm-1/) (e.g., art, food, donations) and [open science conferences](https://openheartmind.org/wisdom-x-aimos-conference/) (e.g., talks, workshops, registration fees), both before the event (e.g., prospective voting for proposed offerings) and after (e.g., retrospective voting for both scheduled and spontaneous contributions).  (-> [read more](https://github.com/openheartmind/WISDOM/wiki/Development-History)).

### Dog-fooding
In addition to fixed-duration events, WisdOHM could also be used to evaluate dynamic contributions to an ongoing project. We intend to prove this concept via the WisdOHM project itself, using WisdOHM to recognise the full range of project contributions, including but not limited to documents, code, donations, and administration tasks. We also intend to explore the concept of a decentralised autonomous funding system, using WisdOHM metrics to distribute any financial contributions that we receive (e.g., donations or grants).

### Prototype
We've released a [working prototype](https://wisdom.openheartmind.org/dashboard) of the app, which allows any community to nominate, review, and recognise a set of contributions with respect to their mission and values. This version was based on our [collective designs and discussions](https://github.com/openheartmind/cOHMunity/wiki/Design-artifacts), but spearheaded by @claymost to enable rapid data collection. At OHM, we're using the app to value past contributions, and to process applications to our OHM Gathering 2025 (November, Gold Coast Hinterland). But the process and app are designed to be generalisable and so we're also interested to see how other communities use it -- please reach out if you do! 

### Minimum Viable Product
Our main focus is on developing a minimal viable product (MVP) -- designed and built through the generous contributions of our international developer team. The MVP will focus on the first three stages of the [broader framework](https://github.com/openheartmind/cOHMunity/wiki/Metavaluation) (Record, Review, Recognise) and will allow any community to create their own instance and populate it with relevant contributions. It's designed to serve our most proven use case: recognising contributions to in-person gatherings, whether they be community arts festivals or research conferences —— but could also be extended to many other use cases. The MVP is similar in design to the prototype, but open source and built collaboratively with the following:

- Well established data model we can use as a basis for any future data analysis.
- Front-end facing application that will engage users with a pairwise comparison voting system. 
- A ‘pairing algorithm’ for assigning contribution pairs to reviewers, and a ‘scoring algorithm’ for assigning values to contributions. These algorithms will be relatively simple for the MVP, but can evolve into more complex algorithms over time. 
- Back-end management server that will manage all collected data and participating users
- Security best practices as we would need to be cautious and mindful of possible cyber security breaches, protecting the data of both users and votes, while also considering the dangers of frauds in the algorithms (Might not make it to MVP but needs a discussion regardless).

#### MVP Project boards
- [All](https://github.com/orgs/openheartmind/projects)
- [Frontend](https://github.com/orgs/openheartmind/projects/21)
- [Backend](https://github.com/orgs/openheartmind/projects/17)
- [Admin](https://github.com/orgs/openheartmind/projects/9)
- [Meetings](https://github.com/orgs/openheartmind/projects/12)

#### MVP Repositories
- [General framework, wiki, issues and project boards](https://github.com/openheartmind/WISDOM)
- [Backend](https://github.com/openheartmind/WISDOM-Backend-MVP)
- [Frontend](https://github.com/openheartmind/WISDOM-Frontend-MVP)
- [Analysis](https://github.com/openheartmind/WISDOM-Analysis-MVP)
