# Concept of the architecture

When you read the current version of the documentation, you may notice that the idea of Aish is to divide Aish into a collection of interconnecting services, hence this is the most common practise of large scale software architecture today.

However, since the Aish is supposed to be inhabiting any device that eventually is able to run any part of its system, to maximise efficiency and spread, we encourage to think of the structure more like cluster of nodes with different specialisations.

Aish is held together by it's value system \(Aish Shares\) that exist in the decentralized blockchain.

* Decentralized Computation
* Decentralized Storage
* Decentralized Value

However as starting point with Aish being able to only operate on a limited amount of machines, the following services, clients and bots are proposed:

## Services

* [Aish Core](/technical-documentation/services/aish-core.md)
* [Aish Data](/technical-documentation/services/aish-data.md)
* [Aish Api](/technical-documentation/services/aish-api.md)
* [Aish Web](/technical-documentation/services/aish-web.md)

### Clients

* [Aish Client](https://www.gitbook.com/book/aish/white-paper-the-greedy-ai/edit#)

### Bots

* [Aish Instagram Bot](/technical-documentation/bots/aish-instagram-bot.md)

### Centralized Databases

* Aish Luther \(aish-luther\) - \[ mongoDB/mLab hosted/aws \] 0.5 GB - crawler data
* Aish Web \(aish-web\) - \[ MySQL/aish.ai \] 1 GB - wordpress user data

## Tech Stack

At the creation of this document a Docker container architecture is proposed, but may require migration at a later point in time.

Each service may have their own technical specifications.

## Experimental Services, Clients & Bots

Provide PoC \(sig. Proof of Concept\) and create awareness of the project. Any of these prototype developments are not fit for production, but may be integrated at the actual start of the project. Their budget is limited to minor arts funding and good will of early project supporters. _There is no guarantee that any of the work or investments provided during this period will result in Aish Shares reimbursements as is outline for the final Aish blockchain logic._

You can find a list of experimental services and clients in each section of the services, clients and bots documentation or in the respective repositories. Visit: www.gitlab.com/aishai/ for a full list of Aish related projects.

# Architectural overview \(visualized\)



