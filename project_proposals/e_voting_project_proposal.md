# e-Voting Project Proposal

## What is the problem

People have been voting on various things since the dawn of civilization. It is a crucial process in many aspects of many entities like countries, societies, companies and more, as voting is usually used to choose a path (in polls) or a person (in elections) to follow with the development of things.
This powerful instrument is easy to exploit though. There are two main attack vectors that voting is subject to:

1. Voting on behalf of other people. This happens during the voting phase, when votes can be cast by people that pretend to be other people.
2. Faking voting results. This happens during the vote counting phase, when votes can be counted wrongly.

## What is the solution

Decentralizing the voting process could completely eliminate faking the voting results and has the potential to greatly reduce the ability to vote on behalf of other people.

I envision this solution to be flexible and to allow for creating different kind of Polls (I use polls as a broader concept on voting, as it allows voting on things and not only on people), like:

- open/closed polls
- weighted/simple polls
- single/multiple choice polls

## Tech stack

- Ethereum as the blockchain, because it is a public blockchain, but other public blockchains can be considered.
- ReactJS + SemanticUI (or any UI framework) for the frontend, because a production bundle can be easily put into a server with Apache/Nginx to serve it.
- IPFS to store metadata related to each poll, so that it is not so expensive to deploy a poll with all the necessary information about the Poll/Election.
- DigitalOcean to spin up a server in which the frontend can be deployed.
- Django backend to store cache.

## Time/Difficulty estimate

Making this project universal can take some time. Now, I don’t have yet a precise amount of time, but a rough estimate would be around 2-3 months of work for 1-2 hours a day.