> # **ARCHIVED**: Work on this repo has moved to https://github.com/cosmos/chain-registry

# Overview

This repository holds data for chains in the cosmos ecosystem, the [registrar](https://github.com/cosmos/cosmos-registrar) can be used to submit chains to the registry.

# Motivation
Conversations in the Interchain [UX Working Group](http://hackmd.io/@okwme/ux-wg) and [Chain Agnostic Improvement Proposals](https://github.com/ChainAgnostic/CAIPs/issues/27) around multi-chain assets have shown the need for a registry to discover chains and keep basic information up-to-date in order to enable communication with these chains.


# Goal
Create and maintain a global chain registry for applications to discover and communicate with different chains that support the [IBC protocol](https://github.com/cosmos/ics). 

* Allow contributors to take ownership of the data they submit
* Provide all information necessary to communicate with each chain
* Introduce state of chains to navigate active/inactive chains easily
* Make the submission process as easy as possible with [cosmos-registrar](https://github.com/cosmos/cosmos-registrar)

To utilize a github repository is seen as an intermediate solution by parts of the interchain community that could be replaced by a more decentralized approach like a registry chain or a solution that is anchored on an existing chain in the future.

# Roadmap

1) Finalize registry specification and mechanisms

2) Test specification with active chains

3) Move to a more decentralized approach with a well tested specification
