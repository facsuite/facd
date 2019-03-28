facd
====

## Facd Overview

Facd is a blockchain-based cryptocurrency with a strong focus on community
input, open governance, and sustainable funding for development. It utilizes a
hybrid proof-of-work and proof-of-stake mining system to ensure that a small
group cannot dominate the flow of transactions or make changes to Facd without
the input of the community.  A unit of the currency is called a `Facd` (FAC).


## Latest Downloads


## What is facd?

facd is a full node implementation of Facd written in Go (golang).

It acts as a fully-validating chain daemon for the Facd cryptocurrency.  facd
maintains the entire past transactional ledger of Facd and allows relaying of
transactions to other Facd nodes around the world.

This software is currently under active development.  It is extremely stable and
has been in production use since February 2016.

The software was originally forked from [btcd](https://github.com/btcsuite/btcd),
which is a bitcoin full node implementation that is still under active
development.  To gain the benefit of btcd's ongoing upgrades, including improved
peer and connection handling, database optimization, and other blockchain
related technology improvements, facd is continuously synced with the btcd
codebase.

## What is a full node?

The term 'full node' is short for 'fully-validating node' and refers to software
that fully validates all transactions and blocks, as opposed to trusting a 3rd
party.  In addition to validating transactions and blocks, nearly all full nodes
also participate in relaying transactions and blocks to other full nodes around
the world, thus forming the peer-to-peer network that is the backbone of the
Facd cryptocurrency.

The full node distinction is important, since full nodes are not the only type
of software participating in the Facd peer network. For instance, there are
'lightweight nodes' which rely on full nodes to serve the transactions, blocks,
and cryptographic proofs they require to function, as well as relay their
transactions to the rest of the global network.

## Why run facd?

As described in the previous section, the Facd cryptocurrency relies on having
a peer-to-peer network of nodes that fully validate all transactions and blocks
and then relay them to other full nodes.

Running a full node with facd contributes to the overall security of the
network, increases the available paths for transactions and blocks to relay,
and helps ensure there are an adequate number of nodes available to serve
lightweight clients, such as Simplified Payment Verification (SPV) wallets.

Without enough full nodes, the network could be unable to expediently serve
users of lightweight clients which could force them to have to rely on
centralized services that significantly reduce privacy and are vulnerable to
censorship.

In terms of individual benefits, since facd fully validates every block and
transaction, it provides the highest security and privacy possible when used in
conjunction with a wallet that also supports directly connecting to it in full
validation mode, such as [dcrwallet (CLI)](https://github.com/Facd/dcrwallet)
and [Facditon (GUI)](https://github.com/Facd/Facditon).

## Minimum Recommended Specifications (facd only)

* 10 GB disk space (as of September 2018, increases over time)
* 1GB memory (RAM)
* ~150MB/day download, ~1.5GB/day upload
  * Plus one-time initial download of the entire block chain
* Windows 7/8.x/10 (server preferred), macOS, Linux
* High uptime

## Getting Started

So, you've decided to help the network by running a full node.  Great!  Running
facd is simple.  All you need to do is install facd on a machine that is
connected to the internet and meets the minimum recommended specifications, and
launch it.

Also, make sure your firewall is configured to allow inbound connections to port
9108.

<a name="Installation" />

## Installing and updating

### Binaries (Windows/Linux/macOS)

Binary releases are provided for common operating systems and architectures:


## Contact

If you have any further questions you can find us at:

https://Facd.org/community

## Issue Tracker

The [integrated github issue tracker](https://github.com/facsuite/facd/issues)
is used for this project.

## License

facd is licensed under the [copyfree](http://copyfree.org) ISC License.
