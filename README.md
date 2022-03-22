# Ethereum Blockchain Developer's Cheatsheet

### Motivation / Intro
I've created this repository with the sole purpose of centralizing various pieces of information that I've deemed useful while learning about blockchain development. 

## Tech stack
### Smart contracts
I recommend working with [Solidity](https://docs.soliditylang.org/en/v0.8.13/#) for writing smart contracts. There are plenty of examples of smart contracts written is [Solidity](https://docs.soliditylang.org/en/v0.8.13/#) and the language itself is rather straight forward. The  [documentation](https://docs.soliditylang.org/en/v0.8.13/#) is also very comprehensive and [Stack Overflow](https://stackoverflow.com/) will probably answer 90% of the questions about the language and its features.

---
### Development environment
There are multiple ways to setup an environment for writing and testing [Solidity](https://docs.soliditylang.org/en/v0.8.13/#) smart contracts. You can even do it directly in the browser, without having to install anything on your local system.
- [Remix](http://remix.ethereum.org/) - in-browser IDE. You can write, deploy and interact with contracts directly from your browser, without any kind of local setup
- [Hardhat](https://hardhat.org/) - Local environment. Developer quality of life oriented environment. Provides a local Eth network, debugging capabilities and extensibility through plugins
- [Truffle](https://trufflesuite.com/truffle/) + [Ganache](https://trufflesuite.com/ganache/)
> My personal recommendation for the dev env would be **Remix** for drafting some basic contracts and **Hardhat** for local development and deployment

---
### Client applications
I would go for a relatively **lightweight** **JavaScript** library or framework in order to build the client facing apps that will interact with your smart contracts. Valid options:
- [React](https://reactjs.org/)
- [Next.js](https://nextjs.org/)
- [Angular](https://angular.io/)
- [Vue.js](https://vuejs.org/)
>My personal recommendation for the frontend tech choice would be either [React](https://reactjs.org/) or [Next.js](https://nextjs.org/)

*JavaScript vs TypeScript* - Totally go for **TypeScript** if you have some degree of **familiarity** with it or you're going for production-level **quality**. For **hackathons** or simple starting-out applications, **JavaScript** would be a better option because of the Ts introduces overhead and has a bigger dev-time cost.

---
### Smart Contract - Web Client interaction
In order to read data and send transactions to your deployed contracts, you will need a way to interact with the blockchain. There are 2 popular library options designed for this:
- [ethers.js](https://docs.ethers.io/v5/) - newer, better structure, cleaner overall
- [web3.js](https://web3js.readthedocs.io/en/v1.3.4/) - larger developer community, more guides

>**Important:** As of the time of writing this document, these 2 libraries are the industry standard and the only options that I know about.

Both options are pretty well documented and offer pretty similar functionality overall.
>My personal preference is [ethers.js](https://docs.ethers.io/v5/)

---
## Learning resources and Guides
- [useWeb3.xyz](https://www.useweb3.xyz/) - courses, guides, books, videos, everything can be found here
- [Ethereum page tutorials](https://ethereum.org/en/developers/tutorials/) - many topics
- [Buildspace](https://buildspace.so/) - tutorials, online workshops, discord community, **requires an account**
- [Guide to Full Stack Ethereum Development by Nader Dabit](https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13) - Great all rounded tutorial for creating a simple end-to-end dApp with [Hardhat](https://hardhat.org/), [React](https://reactjs.org/) and [ethers.js](https://docs.ethers.io/v5/). Also has a [video version](https://www.youtube.com/watch?v=a0osIaAOFSE&ab_channel=NaderDabit) of it if you're not into reading.

>I will add more stuff here over time

>**Important:** If you're an absolute beginer, check out [Nader Dabit's tutorial](https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13). It will give you a hands-on experience and overview of how things are set-up and work.
