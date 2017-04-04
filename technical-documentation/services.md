# Concept of the architecture

When you read the current documentation, you may notice that the idea of Aish is to put divide Aish into a collection of interconnecting services, hence this is the most common practise of large scale software architecture today. 

However since the Aish is supposed to be inhabiting any device that eventually is able to run any part of its system, to maximise efficiency and spread, we encourage to think of the structure more like cluster of nodes with different specialisations. 

Aish is held together by it's value system \(Aish Shares\) that exist in the decentralized blockchain.

* Decentralized Computation
* Decentralized Storage
* Decentralized Value

However as starting point with Aish being able to only operate on a limited amount of machines, the following 5 services are proposed:

## Services

* [Aish Core](/technical-documentation/services/aish-core.md)
* [Aish Data](/technical-documentation/services/aish-data.md)
* [Aish Api](/technical-documentation/services/aish-api.md)
* [Aish Client](/technical-documentation/services/aish-client.md)
* [Aish Web](/technical-documentation/services/aish-web.md)

## Tech Stack

At the creation of this document a Docker container architecture is proposed, but may require migration at a later point in time.

Each service may have their own technical specifications. 



