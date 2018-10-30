# Ticket sale - Project proposal
Whenever you want to work on something for 7ETH, you should sketch these guidelines in an __elevator pitch__ way - keeping it brief but meaningful - so that other developers like your idea and join you... Or just keep it as reference for anyone to clearly understand your project.

### What is the problem
I have bought many tickets for concerts and I'm always very surprised by the high distribution/service fees. I believe it is a very unnecessary step in any kind of ticket sale or RSVP. The only value that the middle man might bring is marketing, but they take a lot of advantage of the power they have and set the fees they want.

### What is the solution
It is widely known that blockchain can be applied to eliminate the middle man in many kinds of transactions. Decentralizing the sale of tickets could completely eliminate the middle man. Any music band could just hire somebody to deploy a smart contract on the blockchain that lets users buy their tickets and stores that data. Any person that goes to the concert could somehow digitally sign or prove that they own an account that has bought a ticket. This also applies to any event that requires RSVP with or without ticket sale.

### Tech stack
- **Ethereum** as the blockchain. Although open to other blockchains, I believe Ethereum has the necessary features for this use case. I'm worried about peak transaction traffic when a big event just starts the sale... Like overhyped ICOs, so I'm open to suggestions or for now it could be implemented on the Ethereum blockchain and expect Casper and sharding to improve tx speed.

- **ReactJS + Webpack + Bootstrap** for the frontend, because a production bundle can be easily put into a server with **Apache/Nginx** to serve it
- **uPort** for the users to authenticate when entering a event
- **IPFS** to store metadata related to each event, so that it is not so expensive to deploy a ticket sale contract as it would only store the IPFS hash to a PDF document that contains all relevant information about the event
- **AWS** to spin up a server in which the frontend can be deployed, if I decide to deploy it and expose it to the world

- **Django** backend to store cache (most used contract addresses of ticket sales), analytics, send emails... If and when necessary

### Time/Difficulty estimate
At first, I want to learn about all the tech stack that I included in this proposal, so it is probably a project to work on for a couple of weeks. If some developers join me and get some good results, I would be happy to take it to the next level and spend some months perfecting it so that I can be proud of it!