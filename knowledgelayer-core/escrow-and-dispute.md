# Escrow and Dispute

The KnowledgeLayer Escrow and Dispute Resolution Module allows for secure payments between users on KnowledgeLayer integrated platforms and between KnowledgeLayer integrated marketplaces.

When a user buys a course the money is not sent directly to the seller, but it is instead locked in an escrow. The buyer has a pre-determined amount of time for trying the course and making sure that it matches the expectations.

If the buyer is satisfied, the seller can claim the locked amount after the trial period expires. On the other hand, if the buyer is not happy with the product, they can open a dispute about the purchase, if the platform allows it.

## Disputes and Arbitration

At the platform level, you can decide whether to allow your users to initiate disputes or not. If you choose to allow for disputes, you must choose which type of arbitration to support.

KnowledgeLayer intends to offer support for various dispute resolution options. The goal is to have arbitration be as modular as possible. The main two options will be the following:

### Kleros Arbitration

Kleros is a dispute protocol with a decentralized network of jurors that act as the arbitrator for disputes. When one user initiates a dispute, the result of the dispute is judged by jurors in the Kleros Court system. A ruling is then sent back to the platform, to be displayed to the users.

By having decentralized multi-party juror dispute resolution, KnowledgeLayer allows platforms to avoid the common pitfalls that come with centrally managed dispute resolutions; namely, biased decisions, high cost of resolution, and inefficiency.

### Platform-Managed Arbitration

Platform-Managed Arbitration is a centralized solution where platforms have the power to rule on the disputes which arise on purchases created with them. This is conducted similar to how most platforms handle disputes today - with customer service agents or administrators deciding rulings.
