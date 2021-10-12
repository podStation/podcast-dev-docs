# Lightning Network

Lightning Network is a _Layer 2_ payment protocol that works on top of blockchain based crypto currencies using smart contracts[^lightning-network-wikipedia].

Lightning currently supports Bitcoin and Litecoin as currencies, but Bitcoin has a higher adoption.

As part of the _Podcasting 2.0_ initiative, monetization based on the Lightning Network was proposed.

[^lightning-network-wikipedia]: [Lightning Network](https://en.wikipedia.org/wiki/Lightning_Network) - Wikipedia Article

## Status

Although it is already supported by a number of hosting platforms and applications, monetization with Lightning Network is still considered **experimental**.

## Advantages

There are some aspects of the Lightning Network that make it attractive as a technology for podcast monetization:

- **Decentralized** - Lightning payments are _peer-to-peer_. Although they may depend on a middle man (for routing payments), the middle man can be any participant of the network, not a central entity. This means that the podcaster cannot be "deplatformed" from a central monetization platform such as _Patreon_ or _PayPal_;
- **Based on open standards** - The fact that the Lightning Network is based on an open standard means that, to a certain extent[^lightning-open-standard-note], the used software can be replaced, avoiding vendor lock-in
- **Fast** - As the name suggests, Lightning payments are nearly instantaneous
- **Allows micropayments**[^wikipedia-micropayment] - Lightning payments can be done with very small amounts (i.e. down to millisatoshis for Bitcoin payments)
- **Low fees** - Once the channels are setup, payments can be done with low (or event zero) fees

[^lightning-open-standard-note]: Although the lightning nodes use an open standard to participate on the network, the APIs to communicate with the nodes are not standardized and vary from node to node.
[^wikipedia-micropayment]: [Micropayment](https://en.wikipedia.org/wiki/Micropayment) - Wikipedia Article

## Disadvantages

Exchanging _fiat money_ into crypto currencies and allocating the crypto in the Lightning Network does have considerable fees. It can also be a difficult process, depending on the setup (i.e. if the participants want to operate their own Lightning Nodes).

## Specification

The specification for monetization with is covered in the specification for the `podcast:value` tag of the _podcast namespace_. This specification can be found [here](https://github.com/Podcastindex-org/podcast-namespace/blob/main/value/value.md).
