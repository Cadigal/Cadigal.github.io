---
layout: post
title: Media for the new age
subtitle: A decentralised and distributed future spanning consciousness and space
cover-img: /assets/img/decentralised.jpg
thumbnail-img: /assets/img/decentralised.jpg
share-img: /assets/img/decentralised.jpg
---

Cover image from https://www.computerhope.com/jargon/d/decentral.htm.

This post is a collected list of tidbits I've written down elsewhere about building a scalable technological base for the future (tech-brain integration, inter-planetary communication).

It's pretty much a consciousness stream. Little is explained and it most likely won't make much sense to the casual reader but I've provided (some) links to referenced resources where possible. Strap in.

See my [previous post about the situation in Ukraine](/2022-02-27-ukraine/)
I've drawn inspiration from many sources, one of my favourite blogs is http://joeduffyblog.com/2015/11/03/blogging-about-midori/.
I'd like this to be a greenfield reimagination of data storage and transfer.

What I want / my vision:
- I want software that can act as my brain for me
- I need to trust it
- It needs to make the decision I would have made
- I want it to hold the data my brain holds
- I want it to do the computations my brain does (analyse the links between data/memories)
- Public files stored in IPFS
- Homomorphic encryption

Keywords:
- Blockchain
- web3
- constellation visualisation
- brain map
- brain storm
- VR
- IPFS
- git
- auto import (from iCloud)
- real-time
- analysis, palantir

Rambling:
- [Ring-Learning With Errors (RLWE)](http://homomorphicencryption.org/introduction/) considered secure against quantum computers!?
- ZFS provides snapshots and data integrity, [IPFS](https://ipfs.io) provides bullet-proof data storage
- IPFS multiplexing
- I can use IPFS in conjunction with ZFS to provide safeguarded data storage that will never get destroyed or decay while humanity exists and stores all previous versions of files
- Probably good to start with [S3](https://github.com/openzfs/zfs/issues/12119) (it’s centralised so likely more reliable for general operation than IPFS currently)
- I can use P2P to transmit data and store it in ZFS 
- ENCRYPT EVERYTHING, use Homomorphic encryption algorithms that allow data transformation on encrypted data without decrypting it
- [HVM](https://github.com/Kindelia/HVM) allows for ubiquious paralellism

Resources:
- https://ipfs.io
- https://www.cossacklabs.com/blog/secure-search-over-encrypted-data-acra-se/
- https://github.com/cossacklabs/rd_themis
