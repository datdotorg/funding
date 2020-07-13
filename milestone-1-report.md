# DatDot - Milestone I

## At a glance:
Progress a bit delayed, but we decided to build the whole basic setup (chain and service logic) and make them run together as a proof of concept. We also spend a significant amount of time to create detailed specification so we can now deliver all the milestones in a way shorter time.

Deliverables completed: 6/5

## Overview:

In this milestone we committed to 5 deliverables:

#### (Completed) D1: Working SRML module
https://github.com/playproject-io/datdot-substrate/tree/master/datdot-node/pallets/datdot

#### (Completed) D3: Basic javascript module as a helper to interact with the node
https://github.com/playproject-io/datdot-service/blob/dev/lab/scenarios/mvp-1.js

We basically managed to already create a docker container which runs both, the chain and the service and sends the transactions and does the whole basic hosting service.

#### (Completed) D4: A screencast that explains how a user can spin up one of those Substrate nodes.
https://www.loom.com/share/9a861cffba244c089efa094e15979cd2

#### (Completed) D5: Once the node is up, it will be possible to send test transactions that will show how the new functionality works and will create a screencast which shows step by step how it works
https://www.loom.com/share/7d0aee905e26412894904c2c6efacfac

#### (Completed) D2: Docker container that runs a substrate node using the module and a little demo screencast
https://hub.docker.com/repository/docker/ninabreznik/datdot
https://hackmd.io/7MxNA_CVSVej4vBCtAIsjw
https://www.loom.com/share/159150db48eb4d7da11c9363d3fd3646

#### Additional (Completed) D6: A detailed specification and documentation with the APIs for the Milestone I
https://hackmd.io/VuD_bziuTN654YL8LE3LuA?view

#### Additional: see below in the Milestones II and III

Most of this past months was spent to spec out the details about the roles needed to make this p2p hosting solution work and the economic model with incentives for all these roles. We figured out it makes more sense to spend more time working on the specification than to have to refactor the whole code once we stumble upon the problem.

Next to this, we also set up the structure of the project and making sure all the environments (substrate, javascript, dat and crypto) will work together.

We tinkered with some basic API setups for the CHAIN and the SERVICE in the service logic and also with the API for the pallet. We also prepared the basic documentation which will be updated for each milestone.

We are hoping to complete the next milestones faster, since we now have the specifications, environment and the processes setup.

Thanks for reading and hope you all have a happy and stress-free week!

## What's Next

### Milestone II
D1: Refined working SRML module

(In progress) D2: Refined javascript module that helps interacting with the node
We already implemented the basic logic of creating using Dat protocol, hosting it and retreiving it from the storage by the hoster to respond to the challenges (as a proof of storage and proof of retrievability). Now in the Milestone II will will focus to make this more robust.

(In progress) D3: Basic web UI which works with a locally running substrate node

(Completed) D4: Docker container that runs both together: substrate and service
https://hub.docker.com/repository/docker/ninabreznik/datdot

D5: Screencast that explains how a user can spin up the docker and use it

### Milestone III

(In progress) D1: Working electron task bar application to run the substrate node and UI
https://github.com/playproject-io/datdot-wallet

D2: Report with the results from the analysis of our public beta

(In progress) D3: Refine and describe the economic model we are using
https://hackmd.io/3wUae9JDRMmS1zQesToMcg?view
https://github.com/playproject-io/datdot-research/blob/master/spec/latest.md

D4: Record a screen cast to show how to install and use the electron app to pin your data or let it be pinned

(In progress) D5: Detailed documentation which explains all
https://hackmd.io/04mCttfxT4Ww9i4KjLIz5A
