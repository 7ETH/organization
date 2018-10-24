## Guidelines for new project proposals
Whenever you want to work on something for 7ETH, you should sketch these guidelines in an __elevator pitch__ way - keeping it brief but meaningful - so that other developers like your idea and join you... Or just keep it as reference for anyone to clearly understand your project.

### What is the problem
Explain what you are trying to solve, why that is a problem. Learning is a good excuse to work on something, but if possible, that something should solve a problem. This way, the project will gain more attraction.

> A couple of weeks ago I bought a ticket for an Aerosmith concert... It cost me $90! But the worst part is the service fee, it was like 30% of the price... That is the middle man that takes advantage of the power of being the only seller of those tickets.

### What is the solution
Give a brief explanation about how a blockchain application could solve the problem.

> Decentralizing the sale of tickets could completely eliminate the middle man. Any music band could just hire somebody to deploy a smart contract on the blockchain that lets users buy their tickets and stores that data. Any person that goes to the concert could somehow digitally sign or prove that they own an account that has bought a ticket. This also applies to any event that requires RSVP with or without ticket sale.

### Tech stack
List the tools and technologies that you are planning to use for this project. A reason for each one would be appreciated.
> Ethereum as the blockchain, because it is the most used one / I have experience with it already / It is a public blockchain 
> ReactJS + Webpack + Bootstrap for the frontend, because a production bundle can be easily put into a server with Apache/Nginx to serve it
> uPort for the users to authenticate when entering a event
> IPFS to store metadata related to each event, so that it is not so expensive to deploy a ticket sale contract as it would only store the IPFS hash to a PDF document that contains all relevant information about the event
> AWS to spin up a server in which the frontend can be deployed, if I decide to deploy it and expose it to the world
> Django backend to store cache (most used contract addresses of ticket sales), analytics, send emails...

### Time/Difficulty estimate
Try to think how serious you want this project to be, take into account the installation of new tools that you might want to use, divide the project into smaller tasks and try to estimate each one of them. Or you can just estimate if it would take days, weeks or months.
> At first, I want to learn about all the tech stack that I included in this proposal, so it is probably a project to work on for a couple of weeks. If some developers join me and get some good results, I would be happy to take it to the next level and spend some months perfecting it so that I can be proud of it!

### Examples of good proposals
TODO Include a list of links to good proposals once we have...